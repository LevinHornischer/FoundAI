Welcome to the course _Advanced Topics in the Foundations of AI_! It is given during the summer semester 2024 at _LMU Munich_ as part of the _Master in Logic and Philosophy of Science_. 


# Motivation 

In recent years, artificial intelligence and, in particular, machine learning made great---but also disconcerting---progress. However, their foundations are, unlike other areas of computer science, less well understood. This seminar is about the mathematical foundation of AI. After a review of the classical theory (Computability Theory, No-Free-Lunch Theorem, Universal Approximation Theorem, etc.), we read some recent research papers to get an overview of some current approaches to the foundations of AI. The course aims to convey not only the knowledge of these extant approaches, but also the skill to mathematically develop and philosophically assess them.

# General information

The instructor of the seminar is me, [Levin Hornischer](https://www.mcmp.philosophie.uni-muenchen.de/people/faculty/hornischer_levin/index.html). During the semester, we meet on Wednesdays from 12:15 to 13:45 in room 021 (Ludwigstr. 31). Below you find a schedule of when we cover which topic. 

# Reader

You find the latest edition of the reader in this file: [`found-ai.pdf`](found-ai.pdf). It will be updated as the course progresses.


# Formalities

All the organizational details for the course are described in this file: [`formalities.pdf`](formalities.pdf).


# Schedule

The schedule below describes in which week we will cover which material. Here 'chapter' refers to the chapter of the reader.

Week | Date | Chapter | Topic | Main reading | Additional material
---  | ---  | ---     | ---   | ---          | ---   
 1 | 17 Apr | 1 | Course intro | -  | - 
 2 | 24 Apr | 2 | Introduction to AI | Russell and Norvig (2021, ch. 1) |  The additional material mentioned in ch. 2
 3 | 1 May  | - | _cancelled_ (Labour Day) | - | - 
 4 | 8 May  | 3 | Symbolic AI | Flasinski (2016, ch. 2) and Immerman 2021 | - 
 5 | 15 May | 4 | Statistical learning theory | Shalev-Shwartz and Ben-David (2014, ch. 5 and sec. 6.1-4) | As background also ch. 2-3 
 6 | 22 May | 4 | Universal approximation | Hornik et al. (1989) | Kratsios (2021, sec. 1-3)
 7 | 29 May | 5 | Learning theory for neural nets | Berner et al. (2022, pp. 1-31) | Belkin (2021, sec. 1-3)
 8 | 5 Jun  | TBA | TBA | TBA | TBA 
 9 | 12 Jun | TBA | TBA | TBA | TBA 
10 | 19 Jun | TBA | TBA | TBA | TBA 
11 | 26 Jun | TBA | TBA | TBA | TBA 
12 | 3 Jul  | TBA | TBA | TBA | TBA 
13 | 11 Jul | TBA | TBA | TBA | TBA 
14 | 17 Jul | TBA | TBA | TBA | TBA 


# Essay topic

Below are some possible essay topics. I'll extend this list as the course progresses.

* _Theory of ML_. It is common to hear that we need a theory of machine learning. But it is less clear how such a theory should look like. What should it be able to do? Maybe learning guarantees: that this neural network architecture with that dataset will learn the true function after so and so many steps? Or interpretability: that a human-understandable description of what the neural network does can be given so and so? Or verification: that a this machine learning system will only produce safe (i.e., fair, unbiased, non-harmful, etc.) behavior? Looking at the philosophy of science literature, can you find—and argue for and again—desiderata for a theory of ML?
* _Interpretations of the No-Free-Lunch theorem_. There is an extended discussion on the interpretation of the No-Free-Lunch theorem and how it connects to the philosophical problem of induction (see, e.g., Sterkenburg and
Grünwald 2021). What can you say for the specific case where the learner is a neural network: how does it cope with the problem of induction? Also take into account how neural networks seem to defy the usual conclusion bias-complexity tradeoff (e.g., Belkin 2021 and  Berner et al. 2022).


Just to be sure, these suggested topics are meant as first ideas. It is part of the task of writing an essay to turn an interesting aspect of the suggested topic into a precise research question and collect the relevant literature on it. Please take a look at the grading criteria mentioned in the file [`formalities.pdf`](formalities.pdf) to get a clear idea of what a good essay is expected to look like.
