Welcome to the course _Advanced Topics in the Foundations of AI_! It is given during the summer semester 2025 at _LMU Munich_ as part of the _Master in Logic and Philosophy of Science_. (Past editions: summer 2023, summer 2024.)


# Motivation 

In recent years, artificial intelligence and, in particular, machine learning made great---but also disconcerting---progress. However, their foundations are, unlike other areas of computer science, less well understood. This seminar is about the mathematical foundation of AI. After a review of the classical theory (Computability Theory, No-Free-Lunch Theorem, Universal Approximation Theorem, etc.), we read some recent research papers to get an overview of some current approaches to the foundations of AI. The course aims to convey not only the knowledge of these extant approaches, but also the skill to mathematically develop and philosophically assess them.

# General information

The instructor of the seminar is me, [Levin Hornischer](https://www.mcmp.philosophie.uni-muenchen.de/people/faculty/hornischer_levin/index.html). During the semester, we meet on Wednesdays from 10:15 to 11:45 in room 028 (Ludwigstr. 31). Below you find a schedule of when we cover which topic. 

# Reader

You find the latest edition of the reader in this file: [`found-ai.pdf`](found-ai.pdf). It will be updated as the course progresses.


# Formalities

All the organizational details for the course are described in this file: [`formalities.pdf`](formalities.pdf).


# Schedule

The schedule below describes in which week we will cover which material. Here 'chapter' refers to the chapter of the reader.

Week | Date | Chapter | Topic | Main reading | Additional material
---  | ---  | ---     | ---   | ---          | ---   
 1 | 23 Apr | 1   | Course intro | -  | - 
 2 | 30 Apr | 2   | Introduction to AI | Russell and Norvig 2021, ch. 1 | See 'further material' in reader, ch. 2 
 3 | 7 May  | 2   | Introduction to AI | Do [coding exercise](https://colab.research.google.com/drive/1VDFm5iHMD2L57CisLdOqY9We7bYoCLV-?usp=sharing) and browse 'further material' in ch. 2 to solidify the concepts discussed in class on 30 April | 
 4 | 14 May | 3   | Computability theory | Flasiński (2016, ch. 2) | Immerman (2021)  |
 5 | 21 May | TBA |  |  |
 6 | 28 May | TBA |  |  |
 7 | 4 Jun  | TBA |  |  |
 8 | 11 Jun | TBA |  |  |
 9 | 18 Jun | TBA |  |  |
10 | 25 Jun | TBA |  |  |
11 | 2 Jul  | TBA |  |  |
12 | 9 Jul  | TBA |  |  |
13 | 16 Jul | TBA |  |  |
14 | 23 Jul | -   | Term paper discussion | - | -

# Essay topics

Below are some possible essay topics (I might add more during the course).

* _On the idea of a theory of machine learning_. It is common to hear that we need a theory of machine learning. But it is less clear how such a theory should look like. What should it be able to do? Maybe learning guarantees: that this neural network architecture with that dataset will learn the true function after so and so many steps? Or interpretability: that a human-understandable description of what the neural network does can be given so and so? Or verification: that this machine learning system will only produce safe (i.e., fair, unbiased, non-harmful, etc.) behavior? Looking at the philosophy of science literature, can you find—and argue for and against—desiderata for a theory of ML? Does the theory that we have for symbolic AI meet those desiderata?
* _The No-Free-Lunch theorem and the problem of induction_. There is an extended discussion on the interpretation of the No-Free-Lunch theorem and how it connects to the philosophical problem of induction (see, e.g., Sterkenburg and
Grünwald 2021). What can you say for the specific case where the learner is a neural network: how does it cope with the problem of induction? Also take into account how neural networks seem to defy the usual conclusion bias-complexity tradeoff (e.g., Belkin 2021 and  Berner et al. 2022). In particular, consider Belkin's suggestion the inductive bias of modern, over-parametrized neural networks is an instance of Occam’s razor: among the explanations that are consistent with the evidence (i.e., the prediction rules that interpolate the training data) pick the simplest one (i.e., the smoothest one).
* _Assessing the statistical mechanics approach to neural networks_. Assume you have a method to analytically compute the probability distribution of which neural network you end up with conditioned on the learning algorithm and training data that you use—discussed by Roberts and Yaida (2022, p. 7). Which aspects of a theory of machine learning have you then achieved? Which are still missing? Besides the many analogies between statistical mechanics in physics and neural networks in machine learning, can you also think of disanalogies? 

Just to be sure, these suggested topics are meant as first ideas. It is part of the task of writing an essay to turn an interesting aspect of the suggested topic into a precise research question and collect the relevant literature on it. Please take a look at the grading criteria mentioned in the file [`formalities.pdf`](formalities.pdf) to get a clear idea of what a good essay is expected to look like.
