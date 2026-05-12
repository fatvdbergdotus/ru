(c) 2026 Freek van den Berg. All rights reserved.

# Languages and Automata: Practical Paper about Sokoban

**Freek van den Berg**  
S0517593  
January 8th, 2008

## Introduction

For the course Languages and Automata at the Radboud University Nijmegen, a practical example has been chosen by me in which the theory learned in the course is applied on a practical situation. I've chosen to describe Sokoban as a language decision problem, after which the grammar can be derived from a Sokoban level. First I'll explain something about Sokoban briefly, after which the theory learned in the course will be directly linked to Sokoban in several ways.

## What is Sokoban?

Sokoban is developed in Japan by Hiroyuki Imabayashi and is a transport puzzling game. The aim of the game is to have the Sokoban, a warehouse keeper, push different boxes and deliver them all to a goal state.

The legal moves a Sokoban can make are North, East, South and West, of which in the current starting position only North will lead to a different state.

## How can Sokoban be described as a language decision problem?

A level of Sokoban can be seen as a language, while the words of this language contain all the move combinations which lead to a solution of this level.

Example alphabet:

```text
{N, E, S, W}
```

Example Sokoban level in ASCII format:

```text
#####
#@$.#
#####
```

Legend:

- `#` = wall
- `@` = sokoban
- `$` = box
- `.` = goal square
- `+` = sokoban on a goal square
- `*` = box on a goal square

## A simple level example

For a level with `X × Y` squares, one Sokoban and `B` boxes, the number of possible states is:

```text
XY * ((XY - 1) above B)
```

The example discussed in the paper has:

- 3 × 3 board
- 1 Sokoban
- 1 box
- 72 possible states

### Example grammar

```text
S -> eS | nA | sG | w
A -> eA | nA | sS | wB
B -> nB | eA | wC
C -> nC | eB | wC | sD
D -> nC | wD | sE
E -> sE | wE | nD | eF
F -> sF | wE | eG
G -> nS | eG | sG | wF
```

## The pump lemma

Whenever the length of a solution exceeds the number of states, the pump lemma implies that some state must repeat.

Example:

```text
N^500 SL
```

can be pumped into:

```text
N^500 N^K SL
```

where `K > 0`.

## An infinite Sokoban level

Without surrounding walls, Sokoban can move infinitely in every direction.

Example solution form:

```text
E^K W^(K+1)
```

with `K > 0`.

Another example:

```text
N^K S^K E^L W^(L+1)
```

with `K > 0` and `L > 0`.

## Conclusion

This paper showed how finite Sokoban levels can be expressed as language decision problems using machines and grammars, and briefly explored how infinite Sokoban levels can be modeled with context-free grammars.

## References

1. Sokoban homepage: http://www.cs.ualberta.ca/~games/Sokoban/
2. *Languages and Machines* by Thomas A. Sudkamp, 3rd edition
