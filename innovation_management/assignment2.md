# Freek van den Berg s0517593

# Innovation Management: Homework Assignment 2

## Managing External Information for Innovation Performance Purposes

October 26th, 2009

---

## Introduction

This paper critically reviews an article written by Frishhammer et al. in 2005 [1]. The paper deals with companies managing external information and the effect it has on innovation performance. The review consists of four steps.

First, the purpose of the paper is determined. Once this step has been taken, a conceptual model and its limitations are given. The authors gathered data, and the way this data has been gathered and the results of it form the third step. This is concluded by stating how this information can actually be meaningful to managers.

---

## Purpose

The paper deals with determining what information from the external environment needs to be gathered, shared, and used in order to stimulate innovation performance as much as possible.

When empirical evidence can be found for or against one or more of these factors having an effect, knowledge about how to manage external information can be obtained. This can both have consequences for research about how to structure a company and for practical use about how to manage a company with respect to the external environment.

---

## Conceptual Model and Its Limitations

For the conceptual language, the formal language ORM (Object Role Modeling) [2] has been used, a language ideally suited for describing concepts and their relationships.

After reading the paper, the following taxonomy could be defined:

```text
Environmental Information
├── General Environmental Information
└── Industry-Specific Information

Management
├── Gathering
├── Sharing
│   └── Cross-functional Integration
│       ├── Personal Interaction
│       └── Impersonal Interaction
└── Using
    └── Decision Making

Innovation Performance
```

The above conceptual model shows the two main concepts: **environmental information** and **innovation performance**.

The environmental information consists of either:

- General environmental information
- Industry-specific information

To connect both concepts, management plays a role. Management deals with gathering, sharing, and using environmental information in order to achieve innovation performance.

For every process, methods are named in the paper to realize them. Some concepts are elaborated further by using subtypes, indicated by arrows. For example:

- Cross-functional integration can be achieved through:
  - Personal interactions
  - Impersonal interactions

The model should merely be used as a first impression of how everything in the paper is related and the vision the authors have on the domain.

### Limitations

The major limitation of such a model is that the concepts are not formally defined and therefore require a lot of intuition (which is subjective) from a human to be interpreted.

Also, the concepts describe an idealized view of reality, while in practice information could be both general and industrial, or difficult to classify at all.

The model does, however, make it possible to position the four hypotheses the authors provide in a bigger perspective.

---

## Hypotheses

### Hypothesis 1

> There is a positive association between scanning of the industry sector of the environment and innovation performance.

Pseudo-mathematical representation:

```text
Gathering + Industry environment -> + Innovation Performance
```

### Hypothesis 2

> There is a positive association between scanning of the general sector of the environment and innovation performance.

```text
Gathering + General environment -> + Innovation Performance
```

### Hypothesis 3

> There is a positive association between integration and innovation performance in organizations.

```text
Sharing (through cross-functional integration) -> + Innovation Performance
```

### Hypothesis 4

> There is a positive association between decision making based on environmental information and innovation performance.

```text
Using (through decision making) + Environmental information -> + Innovation Performance
```

---

## Data Gathering and Results

The data was gathered through a mail survey among Swedish firms classified as manufacturers with 175 to 2500 employees.

The firms needed to have in-house product development.

After a first mailing wave to 344 firms, 330 firms remained for hypothesis testing.

The hypotheses were tested empirically using statistical measures.

---

### Hypothesis 1 Results

Hypothesis 1 was rejected.

It turned out that focusing on the industry had a negative effect.

```text
Gathering + Industry environment -> - Innovation Performance
```

#### Explanation

The possible explanation given by the authors is that seeing what competitors do and what customers want constrains innovative thinking.

Also, looking around and copying might lead to implementing constructs that have not yet been accepted.

---

### Hypothesis 2 Results

Hypothesis 2 was partially accepted.

Only the technology part showed a positive correlation.

```text
Gathering + General technology environment -> + Innovation Performance
```

```text
Gathering + General economy environment -> - Innovation Performance
```

```text
Gathering + General demographic environment -> - Innovation Performance
```

#### Explanation

The economy and demographics may be too broad to lead to branch-specific advantages, while technology can always be applied.

---

### Hypothesis 3 Results

Hypothesis 3 was also partially accepted.

Only personal interaction showed a positive association with innovation performance.

Impersonal interaction turned out to be insignificant.

```text
Sharing (through cross-functional integration, Personal) -> + Innovation Performance
```

```text
Sharing (through cross-functional integration, Impersonal) -> = Innovation Performance
```

#### Explanation

These results are supported by various papers that state collaboration is preferred above interaction and therefore requires a personal touch.

---

### Hypothesis 4 Results

Hypothesis 4 was accepted, but only when decision making involved industry factors.

```text
Using (through decision making), general information -> = Innovation Performance
```

```text
Using (through decision making), industry information -> + Innovation Performance
```

#### Explanation

The explanation given by the authors is that if information is not used, it is useless to gather and share it.

However, an explanation about why general information has no effect is lacking.

---

## Practical Use for Managers

The findings can relatively directly be translated into consequences for three aspects:

1. Input (gathering)
2. Process (sharing)
3. Output (using / decision making)

### Input

Focus mainly on technological information from the general environment.

- Demographical and economical information will have no effect on performance.
- Focusing on industry information (customers, competitors, suppliers) might negatively affect innovation because it constrains innovative thinking.

### Process

Encourage collaboration above interaction, since effective sharing of information requires deep-level sharing between individuals.

### Output

Ensure that the mostly general information obtained during input is translated into industry-specific solutions during the process phase.

Decision making should focus on industry-specific information.

Applying general external information in decision making will have no effect.

---

## Conclusion

A paper by Frishammar et al. about managing external information in order to improve innovation performance has been critically reviewed.

This led to a conceptual model in which the four hypotheses of the authors could be positioned.

These hypotheses were empirically tested and mostly at least partly accepted.

It turns out there are three processes in dealing with external information:

1. Gathering
2. Sharing
3. Decision making

The first process should focus mostly on technological aspects in the general environment and not on the industry environment.

Sharing should happen through intense collaboration, while simple interaction is ineffective.

Decision making should be based on industry environment information.

These findings were translated into practical managerial recommendations.

---

## References

1. Frishammar et al. (2005), *Managing External Information in Manufacturing Firms: The Impact on Innovation Performance*, Journal of Product Innovation Management, Vol. 22, Issue 3, pp. 251–266.

2. T. Halpin, *Object-role modeling (ORM/NIAM)*, Handbook on Architectures of Information Systems, Springer, 1998.
