(c) 2026 Freek van den Berg. All rights reserved.

Can deterministic systems produce behavior that seems autonomous to humans?		
Version 2 beta
























May 22th, 2007

Freek van den Berg S0517593

# Philosophy of Cognition: Can deterministic machines produce behavior that seems autonomous to humans?



## Abstract
In this paper I will show what is needed to give deterministic system behavior that can be classified by humans as autonomous. First a definition of autonomous is given and next some issues that arise when the autonomy is being judged by a human. These issues are demonstrated in 3 different experiments, which preceed a final conclusion.

## Introduction
Let’s have a look at the title of this paper: “Can deterministic machines produce behavior that seems autonomous to humans?” In order to answer this question, two other questions arise, namely “What are deterministic machines?” and “What is autonomous behavior?”.

Starting with the former question about deterministic machines, many paths of research lead to Alan Turing, the father of the Turing Machine. Turing machines are extremely basic abstract symbol-manipulating devices which, despite their simplicity, can be adapted to simulate the logic of any computer that could possibly be constructed (6). Using a Turing machine in conceptual thinking, instead of some random computer, makes it easier to abstract from things that are irrelevant. The main properties of the Turing machine that are relevant for this paper are: a finite amount of states, the ability to communicate with some external source of memory and a chronological set of sequential states occuring. These three properties shall be used for reference in the continuation of this paper.

Next autonomous behavior needs to be clarified. Behavior is about an agent or object acting in it's enviroment by changing its state of it. In order to make the behavior autonomous, something in it needs to be distinguising. Wikipedia offers the following description for autonomous(7): “One who gives oneself his own law, means freedom from external authority.” and the dictionary states: “ Self-government or the right of self-government; self-determination.” An extended view about autonomy shall be given in the next chapter of this paper.

## Autonomy
Investigating the human behavior conceptually brings up a way in which it can be categorized. It's made up by a biophysical and a intentional part. The biophysical part [2] is about using physics to describe biological behavior. Some important topics here include food, temperature, water and light. 
They are interesting in regard to autonomy, because they cause behavior that is essential for our viability. This leads to the effect that in order to maintain viable, a human needs to obey these needs, wanted or not, causing behavior that depends on the way the environment offers these essential needs. This causes behavior that is completely against the definitions of autonomy as stated before, and therefore this part shall not being investigated in this paper.

The second category covers all the behavior that's not in the first and is labeled intentional. This category contains behavior that's not directly caused by physics and/or needed to survive. One can question whether after defining the first category, anything is left for the second. In other words, isn't all behavior a reaction to our environment in order to survive in a world of physics. Even when this is the case, it could still be because of rules that might always remain unknown and therefore making it legitimate to pretend such rules don't exist.

Assuming such rules don't exist or are not detectable, induces a question about how to model this behavior and reason about it. A distinction using a television metaphor could be made. Imagine a tv having 3 different channels. On channel 1 a static test screen is shown. On channel 2 a program you like (could be anything of interest to you) is broadcasted and finally on channel 3 there is no signal and the well known snow (random changing black and white pixels) appears. Channel 1 and 3 can be considered extremes and channel 2 is somewhere in the middle. Although there is no strict seperation between the three channels (channel 2 is partly predictable and partly random), it's very possible to use them to define 3 different levels of autonomy. The different names of the categories chosen are fully deterministic, undeterministic and random, in which the names respectively link to channel 1 till 3. The distinction is made in how much a state (in this case tv snapshot) depends on its previous state. This relation is strongest in the channel 1 example and descreases along the channels.

The previous paragraph listed the different kinds of autonomy that can be observed. In that case the observer uses the blackbox principle [8] and all that matters is the final behavior shown to the outside world and explicitly not how it's caused. In order to achieve this the white box principle is used. Instead of just looking at the behavior of an agent in an environment, the cause of that behavior is also being investigated. This opens up three important questions: “What is the status of the internal state?”, “How does the environment affect the internal state?” and “How does the internal state affect behavior?”. The ability of answering these questions, depends for a big part of the authority of the observer. That is, the amount of observation the observer has to look inside the entity to see its status, algorithm and/or plan.

## Judging autonomy
After mentioning the above about autonomy, it's time to make up different aspects that should be taken in consideration while judging autonomy regarding the main question of the paper. This brings up 4 subquestions that need to be answered: “Who or what should judge about the level of autonomy?”, “How should this entity judge about autonomy?”, “What is the preknowledge about the entity judging autonomy of the to be tested system?”, “Can the autonomy objectively be tested and judged by a deterministic system?” and “What's the expression power of the to be tested system?”.

The first question, about who should judge, seems very straightforward at first, but still requires some thought. Since the system has to be autonomous for humans, judgement has to be done by humans. But every human is unique, leading to different results for every human testing the system. Another property involved, is the knowledge of the user about the domain in which the autonomous system operates. The more the user knows about this domain, the more it can considered to be an expert in judging the system's behavior.

This is covered by the second question, about how to test the autonomy. It seems best to use empirical methods between judging subjects in order to reduce the fluctuation in results caused by differences between humans. The humans should also test independantly of each other and not being prejudiced in any kind of way. Another aspecting being questioned, is in what kind of way the observer observs from the system. Among others the following options are worth considering: The observer interacts directly with the system and tries to guide this interaction to a path in which revealation of the system being not autonomous is most likely. Second, the observer watches the system interact with another entity and makes as many notes as possible about suspicious things.

After picking certain humans to test the system and making up a good test, it's important to make up a profile of the different users. Among different factors that include the way the autonomy is being judged are: age, education, culture, language and religion. Another aspect needed to be taken in account, is the previously named white box principle. That is, what does the observer know about the system that needs to show autonomous behavior? By example, does the observer has access to the internal state of the system, or does the observer know how the algorithms work that are used to make an interaction between the internal state and environment. When the observer has (partial) knowledge about these elements, it can mathematically explain behavior and even more important, do accurate predictions about future behavior, being very unlike autonomy.


Fourth it could be tested whether the prediction of the supposed to be autonomous system has deterministic features. Revising the earlier mentioned tv methaphor showed two extremes. In one case (with the test screen) an algorithm can be found that completely describes the behavior of the autonomous system, without any exceptions. A deterministic system could be connected to the interface of the to be tested system and due complex mathematical calculations a search for regularity can be done. 
In case of the other extreme (a completely random system) the search for regularity can be done emperically. This can be achieved by simulating different actions while being connected to the autonomous system and try to find some weights to describe the likelyhood of a certain reply. After a network containing those corresponding likelyhoods (often a neural network) has been trained, it's performance can be tested by giving this network the same input as the to be tested system. Main point of doing this kind of research, is to check whether the behaviour of the to be tested autonomous system can be predicted in some way depending on enviroment input and thus be used to make a new system with the same behavior. When it's possible to copy a system in that way, it's reasonable to consider it not autonomous. Of course it's very important to keep in mind that the deterministic system testing the complexity, should only be used as an analyising tool, and when results are obtained from this approach, it should be possible to explain the pattern to the observer.

Finally the reception and expression power of the to be tested system need revision. This concerns the bandwith in which the system can interact with its environment, both input and output channels. The sensory channels' (input) bandwidth determines how much data per time unit can enter the system from the enviroment. The higher this value is, the more the system can know about its environment and the more intelligent the behavior of the system can become. This is not a concern for testing autonomy except for having to make sure the right and right amount of information is being provided to the system. The expression power is about how much information the system can provide (=act) to the environment. The lower this bandwith is, this more testing will be needed in order to either make the system convince it's autonomous or showing it isn't. This is something to take in consideration while having the observer test the system and means that the less this bandwidth is, the more testing will be required.

## Different examples
Now that criteria have been analyzed for judging autonomy, some examples of various kind can be evaluated using those criteria. In order to cover most of the examples covered in autonomy 3 examples have been chosen, namely Chessmaster, a cricket game and the Turing test. Every example will be shortly introduced, and then matched to the criteria in terms of what needs to be taken in account in setting up an experiment.

## Chessmaster
Chessmaster 9000 (5)  is a chess software product for PC which offers an application and chess engine to play chess. The remarkable part of the engine is a configuration unit, in which the user can configure its own chess player with certain desires and needs, such as wanting to trade of material quickly, having a favor for keeping bishops above knights or keeping the game closed. After making such a custom player, one can play against it or make it play against another computer opponent. The Chessmaster engine can offer this service by not always picking the best move, but when moves are almost similarly good, picking by example the 2nd best, because it’s matches the player profile better. This will lead to a sacrifice in performance, but since recently chess computers have outperformed humans, it shouldn’t be a problem. 


In how to judge the autonomy the first question that arises is who should judge a system like Chessmaster in its attempt to show autonomous behavior. Because of their knowledge about the domain of playing chess, professional chess players would be very good candidates.
After finding those right and sufficient candidates the way of testing has to be thought of. A way to tackle this challenge is by having a small chess tournament between the chess players and the autonomous system, in which they all play on a computer interface in order to not reveal who they're playing.
It's assumable that among the random distribution of chess players, different ages, cultures, religion and education backgrounds are represented. So that evens out any chance of certain preferences playing a role in judging the autonomy, since an average is taken out of the subject's findings. Investigating the knowledge of the chess players about computer systems, neural networks and chess algorithms might be more troublesome. Since chess players studied much on their domain and often used computers to check their theories, some knowledge of chess algorithms, induces that the chess players have somewhat of a white box view of the system. This results into the system having to use more complicated algorithms in order to hide these properties.
Next, in order to challenge the to be tested system a little more, the chess players (observers) are equiped with a deterministic computer system with which it can make calculations about the input and output channels of the to be tested system. This happends in the so called pre-testing phase. Once the real testing phase starts, use of aiding devices such as computers is not allowed anymore, because it'll prevent the judgement to be completely from a human point of view. However, gained knowledge from pre-testing phase can be used in the testing phase. 
Using this knowledge, the chess player can try to predict moves of its opponents. When a certain level of prediction is achieved, that can be understood by the observer (so guessing excluded), the system can be considered non autonomous, because all its behavior must be a result of the system's environment (the observer is oblivious to the internal state).
Last, but not least, the complexity of the chess game needs some attention. Since the power of expression of a player in a chess game is relatively limited (all rules are known, an average of around 20-30 options per move can be done and no undeterministic features are avaiable), a need to play relatively many games arises. The number of games to be played can be calculated by setting a minimum amount of data the to be tested system needs to reveal in bits. Dividing this value by the number of bits revealed in an average game, results in the number of games to be played.

## Cricket game
In Pacman with crickets (4) test, a human plays the well known computer game pacman, but instead of having opponents being controlled by some deterministic algorithm, they are controlled by real life crickets. This is done by making a physical maze in which the crickets can walk and pointing a webcam at this maze. The input signal from the webcam, is being calculated, to determine the cricket’s location in a 'similar' deterministic world and is shown on the computer screen. Walking around with the pacman, causes parts of the physical maze to vibrate, which results into feedback to the crickets. This experiment just offers an example, and crickets are chosen for economy reasons. When results of these examples turn out to be valuable, different environments and/or different animals might be worth a try.
The final experiment can be set up in a way in which the to be tested autonomous system competes with a system with real crickets. This can easily be done by having the observer watching a computer screen several trials, and not tell at every trial which situation is being observed.


Now that the experiment has been described, it's time to head for the criteria. Since the domain of the experiment is mostly about crickets, it's straightforward to introduce people from this domain in the testing for autonomy phase. Another aspect of the experiment involves the skills of operating a computer game (pacman like) which shouldn't specifically be done by the cricket experts. It sounds reasonable to have someone skilled operate the computer game, while an expert in cricket behavior observes and possibly gives some directions. Of course to reduce subjective judgement as much as possible, different pairs of these people need to be tested on several trials.
As science evolves, more and more knowledge about human and animal behavior becomes avaiable and especially when internal research such as MRI scans and CT scans is done, it's important to keep this in mind regarding the blackboard principle. When too much is known, it could induce that the behavior of the cricket can be predicted to a very accurate level and makes the question emerge whether the cricket still is worth investigating. Although right now, this is not the case yet.
Before the actual experiment (pre testing phase) data from the crickets walking around on the maze could be gained in a sample run. Using mathematical theories and data mining, hypotheses could be set up and tested by a deterministic system. When this knowledge can be converted to something understandable for the subject, this information can be used for testing phase.
Regarding the expression power of the system, some variables can be assigned that are crucial:  The number of distinct positions that can be derived from the webcam image for every cricket, the number of crickets in the maze, the update frequency of the positions spotted on camera and the time every game average lasts. Using the combination this features, it's possible to determine the amount of information that can be obtained from every played game. Setting a minimum amount of information needed to judge the autonomous system, implies the number of games that minimally need to be played.

## Turing test
In the Turing (3) test a human (which has to make a decision) communicates with another human (having to fool or outperform a computer system) and an ‘intelligent’ computer through an interface based on computers (by example chat program) and has to determine which one is the ‘intelligent’ computer. If the ‘intelligent’ computer can fool the human in at least 50% of the cases, making it believe it's a human, it has passed the Turing test.

It's very straight forward that two humans are involved in this test, namely a decision making and a 'fooling' human which has to outperform the computer in some way. At the point in which a decision needs to be made about what kind of qualities these humans should have, different believes arise. The 'fooling' human should be an expert in revealing the weak spots of the computer system, and depending on the computer system, different candidates are suitable. In order to make the task as hard as possible on this point, a big variation amoung 'fooling' humans that test the system seems desirable (point 2 of the judging autonomy criteria). In contrast to what might seem at first, the deciding human has a very important task in this experiment too and will have a big impact on the outcome of the test. The task of this person, is to detect which responding entity is a human. Some skills at detecting human behavior might come in handy for this person, and people who professionally deal with judging humans such as psychiatrists, psychologist and doctors enjoy preference. Another important property of this test is that in order to keep the test fair, no prior communication in any kind of way may exist between judger and observer, since arangements could be made to improve the detection procedure. To completely be sure of this, judger and observer have to be completely unrelated with each other in any way.

Due datamining in previous test results (so all the information the deterministic system has generated) a pattern could be found, and when it's easy enough for a human to understand, it can be used by the observer and/or judger in order to support their task.

Following the third criterium for judiging autonomy, it's important to know what both the observer and judger know about the deterministic system. This includes alghortihm that generates a reply in natural language, the way of storing information to support a cognitive system and the way input is interpeted. Either the observer or judger having such information can make it much harder for the deterministic system to pass the test.
Finally the expression power of the turing test is worth revising. The input and output channels of the deterministic system consist of streams of ASCII characters that represent messages, in which ASCII characters are just 8 bits each. This induces that no conversion between a deterministic and non-deterministic in either direction needs to be made, since this conversion is done when the observer and judger strike the keyboard and at first look seem relatively simple. Zooming in deeper on the details of the Turing test, reveals 3 things in which Alan Turing hasn't made a decision: What's the length of every message (a user could copy/paste text), what's the minimum time interval between messages (even when this value is very small, it only matters what time difference humans can observe) and for how long should the system be tested in order to pass the Turing test? Depending on these answers, the freedom of expression can vary from very limited to an unlimited system.

## Conclusion
In order to talk about autonomy, it's been shown to be very important to define what is meant by it at first. Since the main point has been to let a system be autonomous to humans, the judgement of it is completely done by humans, no matter what the exact concept being meant it. Different kinds of behavior are being discussed, intentional and unintentional and autonomy is being placed in an order between completely predictable and completely random.
After defining this, 5 parameters can be named that have impact on the final result of the judgement. In short they are about who tests the system, how is it tested, what's preknowledge of the system for the user, how much performance is expected from the system and can the way the system works been revealed to a human using computer assistence? These  parameters are being clearified using 3 sample tests (cricket game, Chessmaster, Turing test). Using the parameters in the tests, shows that even within the different tests very big variations among them can occur. This leads to the conclusion that no general statement can be made about the question of this paper, but when a specific test with specific details is known, it's possible. Also it has become clear that when the observer is not aware of many details of the system, it can be relatively easy to show appearant autonomous behavior.

## Biography
(1) American Psychological Association (APA):
autonomy. (n.d.). The American Heritage® Dictionary of the English Language, Fourth Edition. Retrieved January 29, 2007, from Dictionary.com website: http://dictionary.reference.com/browse/autonomy

[2] Wikipedia’s definition on biophysics: http://en.wikipedia.org/wiki/Biophysics

(3) The turing test: http://cogsci.ucsd.edu/~asaygin/tt/ttest.html

(4) Animal Controlled Computer Games: Playing Pac-Man against Real Crickets http://pong.hku.nl/~wim/bugman.htm

(5) Chessmaster 9000: http://www.gamespot.com/pc/puzzle/chessmaster9000/review.html

[6] Wikipedia’s definition on Turing machine: http://en.wikipedia.org/wiki/Turing_machine
[7] Wikipedia’s definition on autonomy: http://en.wikipedia.org/wiki/Autonomy
[8] Wikipedia’s definition on blackbox: http://en.wikipedia.org/wiki/Black_box_(systems)
