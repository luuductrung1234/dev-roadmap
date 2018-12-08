![Open Source Society University (OSSU)][image-1]

<h3 align="center">Open Source Society University</h3>
<p align="center">
  Path to a free self-taught education in Computer Science!
</p>
<p align="center">
  <a href="https://github.com/sindresorhus/awesome">
    <img alt="Awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
  </a>
  <a href="https://github.com/ossu/computer-science">
	<img alt="Open Source Society University - Computer Science" src="https://img.shields.io/badge/OSSU-computer--science-blue.svg">
  </a>
  <a href="https://www.patreon.com/ossu">
	<img alt="Contribute with OSSU on Patreon" src="https://img.shields.io/badge/Patreon-contribute-yellow.svg">
  </a>
</p>

> This repository is base on [**ossu/computer-science**][1]

# :octocat: Contents

- [Summary][2]
- [About][3]
- [Motivation & Preparation][4]
- [Curriculum][5]
  - [Prerequisites][6]
  - [Introduction to Computer Science][7]
  - [Core CS][8]
  - [Advanced CS][9]
  - [Final project][10]
  - [Pro CS][11]
- [Code of conduct][12]
- [Community][13]
  - [How to show your progress][14]
  - [Team][15]
- [References][16]


# Summary

The OSSU curriculum is a **complete education in computer science** using online materials.
It's not merely for career training or professional development.
It's for those who want a proper, *well-rounded* grounding in concepts fundamental to all computing disciplines,
and for those who have the discipline, will, and (most importantly!) good habits to obtain this education largely on their own,
but with support from a worldwide community of fellow learners.

It is designed according to the degree requirements of undergraduate computer science majors, minus general education (non-CS) requirements,
as it is assumed most of the people following this curriculum are already educated outside the field of CS.
The courses themselves are among the very best in the world, often coming from Harvard, Princeton, MIT, etc.,
but specifically chosen to meet the following criteria.

**Courses must**:
- Be open for enrollment
- Run regularly (ideally in self-paced format, otherwise running at least once a month or so)
- Fulfill the [academic requirements][17] of OSSU
- Fit neatly into the progression of the curriculum with respect to topics and difficulty level
- Be of generally high quality in teaching materials and pedagogical principles

When no course meets the above criteria, the coursework is supplemented with a book.
When there are courses or books that don't fit into the curriculum but are otherwise of high quality,
they belong in [extras/courses][18] or [extras/readings][19].

**Organization**. The curriculum is designed as follows:
- *Intro CS*: for students to try out CS and see if it's right for them
- *Core CS*: corresponds roughly to the first three years of a computer science curriculum, taking classes that all majors would be required to take
- *Advanced CS*: corresponds roughly to the final year of a computer science curriculum, taking electives according to the student's interests
- *Final Project*: a project for students to validate, consolidate, and display their knowledge, to be evaluated by their peers worldwide
- *Pro CS*: graduate-level specializations students can elect to take after completing the above curriculum if they want to maximize their chances of getting a good job

**Duration**. It is possible to finish Core CS within about 2 years if you plan carefully and devote roughly 18-22 hours/week to your studies.
Courses in Core CS should be taken linearly if possible, but since a perfectly linear progression is rarely possible,
each class's prerequisites is specified so that you can design a logical but non-linear progression
based on the class schedules and your own life plans.

**Cost**. All or nearly all course material prior to Pro CS is available for free,
however some courses may charge money for assignments/tests/projects to be graded.
Note that Coursera offers [financial aid][20].
Decide how much or how little to spend based on your own time and budget;
just remember that you can't purchase success!

**Process**. Students can work through the curriculum alone or in groups, in order or out of order.
- For grouping up, please use the [cohorts repository][21] to find or create a cohort suited to you.
- We recommend doing all courses in Core CS, only skipping a course when you are certain that you've already learned the material previously.
- For simplicity, we recommend working through courses (especially Core CS) in order from top to bottom, as they have already been [topologically sorted][22] by their prerequisites.
- Courses in Advanced CS are electives. Choose one subject (e.g. Advanced programming) you want to become an expert in, and take all the courses under that heading. You can also create your own custom subject, but we recommend getting validation from the community on the subject you choose.

**Content policy**. If you plan on showing off some of your coursework publicly, you must share only files that you are allowed to.
*Do NOT disrespect the code of conduct* that you signed in the beginning of each course!

**How to contribute**. Please see [CONTRIBUTING][23].

**Getting help**. Please check our [Frequently Asked Questions][24], and if you cannot find the answer, file an issue or talk to our [friendly community][25]!

## About

This is a **solid path** for those of you who want to complete a **Data Science** course on your own time, **for free**, with courses from the **best universities** in the World.

In our curriculum, we give preference to MOOC (Massive Open Online Course) style courses because these courses were created with our style of learning in mind.

## Motivation & Preparation

Here are two interesting links that can make **all** the difference in your journey.

The first one is a motivational video that shows a guy that went through the "MIT Challenge", which consists of learning the entire **4-year** MIT curriculum for Computer Science in **1 year**.

- [MIT Challenge][26]

The second link is a MOOC that will teach you learning techniques used by experts in art, music, literature, math, science, sports, and many other disciplines. These are **fundamental abilities** to succeed in our journey.

- [Learning How to Learn][27]

# Curriculum

**Curriculum version**: `8.0.0` (see [CHANGELOG][28])

- [Prerequisites][29]
- [Introduction to Computer Science][30]
- [Core CS][31]
  - [Core programming][32]
  - [Core math][33]
  - [Core systems][34]
  - [Core theory][35]
  - [Core applications][36]
- [Advanced CS][37]
  - [Advanced programming][38]
  - [Advanced math][39]
  - [Advanced systems][40]
  - [Advanced theory][41]
  - [Advanced applications][42]
- [Final project][43]
- [Pro CS][44]

---

<br/>
<br/>

## Prerequisites

- [Core CS][45] assumes the student has already taken high school math and physics, including algebra, geometry, and pre-calculus.
Some high school graduates will have already taken AP Calculus, but this is usually only about 3/4 of a college calculus class, so the calculus courses in the curriculum are still recommended.
- [Advanced CS][46] assumes the student has already taken the entirety of Core CS
and is knowledgeable enough now to decide which electives to take.
- Note that [Advanced systems][47] assumes the student has taken a basic physics course (e.g. AP Physics in high school).

## Introduction to Computer Science

These courses will introduce you to the world of computer science.
Both are required, but feel free to skip straight to the second course when CS50 (the first course) moves away from C.
([Why?][48])

**Topics covered**:
`imperative programming`
`procedural programming`
`C`
`manual memory management`
`basic data structures and algorithms`
`Python`
`SQL`
`basic HTML, CSS, JavaScript`
`and more`

Process | Courses | Duration | Effort | Prerequisites
 :--: | :-- | :--: | :--: | :--:
:black\_square\_button: | [Introduction to Computer Science - CS50][49] ([alt][50]) | 12 weeks | 10-20 hours/week | none
:black\_square\_button:  | [Introduction to Computer Science and Programming using Python][51] | 9 weeks | 15 hours/week | high school algebra
:black\_square\_button:  | [Introduction to Computational Thinking and Data Science][52]  _(optional)_ | 10 weeks | 15 hours/week | above
:black\_square\_button:  | [Fundamentals of Computing specialization][53] |  6-9 months | 15 hours/weeks | Knowledge of high school mathematics is required. No previous programming knowledge is required.
:black\_square\_button:  | [Introduction to Scripting in Python specialization][54] _(optional)_ | 4 months | 15 hours/weeks | No prior programming experience is necessary.


<br/>
<br/>


## Core CS

All coursework under Core CS is **required**, unless otherwise indicated.

### Core programming
**Topics covered**:
`functional programming`
`design for testing`
`program requirements`
`common design patterns`
`unit testing`
`object-oriented design`
`Java`
`static typing`
`dynamic typing`
`ML-family languages (via Standard ML)`
`Lisp-family languages (via Racket)`
`Ruby`
`and more`

Process | Courses | Duration | Effort | Prerequisites
 :--: | :-- | :--: | :--: | :--:
:black\_square\_button: | [How to Code - Simple Data][55] | 7 weeks | 8-10 hours/week | none
:black\_square\_button: | [How to Code - Complex Data][56] | 6 weeks | 8-10 hours/week | How to Code: Simple Data
:black\_square\_button: | [Software Construction - Data Abstraction][57] | 6 weeks | 8-10 hours/week | How to Code - Complex Data
:black\_square\_button: | [Software Construction - Object-Oriented Design][58] | 6 weeks | 8-10 hours/week | Software Construction - Data Abstraction
:black\_square\_button: | [Programming Languages, Part A][59] | 4 weeks | 8-16 hours/week | recommended: Java, C
:black\_square\_button: | [Programming Languages, Part B][60] | 3 weeks | 8-16 hours/week | Programming Languages, Part A
:black\_square\_button: | [Programming Languages, Part C][61] | 3 weeks | 8-16 hours/week | Programming Languages, Part B

#### Readings
- **Required** to learn about monads, laziness, purity: [Learn You a Haskell for a Great Good!][62]
  - **Note**: probably the best resource to learn Haskell: [Haskell Programming from First Principles][63] `paid`
- **Required**, to learn about logic programming, backtracking, unification: [Learn Prolog Now!][64]

### Core math

**Practice Place**:
[Practice with Math][65]

**Topics covered**:
`linear transformations`
`matrices`
`vectors`
`mathematical proofs`
`number theory`
`differential calculus`
`integral calculus`
`sequences and series`
`discrete mathematics`
`basic statistics`
`O-notation`
`graph theory`
`vector calculus`
`discrete probability`
`and more`

Process | Courses | Duration | Effort | Prerequisites
 :--: | :-- | :--: | :--: | :--:
:black\_square\_button: | [Discovery Precalculus: A Creative and Connected Approach](https://www.edx.org/course/discovery-precalculus-creative-connected-utaustinx-ut-prec-10-03x) _(optional)_ | - | - | -
:black\_square\_button: | [Pre-Calculus: Function][66] _(optional)_ | - | - | -
:black\_square\_button: | [Pre-Calculus: Trigonometry][67] _(optional)_ | - | - | - 
:black\_square\_button: | [Pre-Calculus][68] ([alt][69]) _(optional)_ | 6 weeks | 6-8 hours/weeks | College Algebra and Problem Solving
:black\_square\_button: | [Essence of Linear Algebra][70] | - | - | pre-calculus
:black\_square\_button: | [Linear Algebra - Foundations to Frontiers][71] ([alt][72]) | 15 weeks | 8 hours/week | Essence of Linear Algebra
:black\_square\_button: | [Calculus One][73]<sup>*1*</sup> ([alt][74]) | 16 weeks | 8-10 hours/week | pre-calculus
:black\_square\_button: | [Calculus Two: Sequences and Series][75]| 7 weeks | 9-10 hours/week | Calculus One
:black\_square\_button: | [Calculus 1A: Differentiation][76] | 13 weeks | 6-10 hours/week | pre-calculus
:black\_square\_button: | [Introduction to Differential Equations][77]   _(optional)_ | 15 weeks | 5-8 hours/week | Single-variable Calculus
:black\_square\_button: | [Differential Equation 2x2 System][78]   _(optional)_  | 9 weeks | 2-5 hours/week | above
:black\_square\_button: | [Differential Equations: Linear Algebra and NxN Systems of Differential Equations]()   _(optional)_  | 9 weeks | 5-8 hours/week | above
:black\_square\_button: | [Calculus 1B: Integration][80] | 13 weeks | 5-10 hours/week | Calculus 1A
:black\_square\_button: | [Calculus 1C: Coordinate Systems & Infinite Series][81] | 13 weeks | 5-10 hours/week | Calculus 1B
:black\_square\_button: | [Calculus Applied][82] _(optional)_ | 7-9 weeks | 3-6 hours/week | Single-variable Calculus (derivatives, integrals and basics of differential equations); College or AP/IB High School Level
:black\_square\_button: | [Mathematics for Computer Science][83] | 13 weeks | 5 hours/week | single variable calculus (Calculus Two)


<sup>**1**</sup>: Students struggling with MIT Math for CS can consider taking the [Discrete Mathematics Specialization][84] first.
It is more interactive but less comprehensive, and it costs money to unlock full interactivity.

### Core systems

**Topics covered**:
`boolean algebra`
`gate logic`
`memory`
`machine language`
`computer architecture`
`assembly`
`machine language`
`virtual machines`
`high-level languages`  
`compilers`
`operating systems`
`network protocols`
`and more`

Process | Courses | Duration | Effort | Prerequisites
 :--: | :-- | :--: | :--: | :--:
:black\_square\_button: | [Build a Modern Computer from First Principles: From Nand to Tetris][85] ([alt][86]) | 6 weeks | 7-13 hours/week | none
:black\_square\_button: | [Build a Modern Computer from First Principles: Nand to Tetris Part II ][87] | 6 weeks | 12-18 hours/week | one of [these programming languages][88], From Nand to Tetris Part I
:black\_square\_button: | [Carnegie Mellon Computer Architecture][89] _(optional)_ | - | - | -
:black\_square\_button: | [Introduction to Computer Networking][90]| 8 weeks | 4–12 hours/week | algebra, probability, basic CS
:black\_square\_button: | [ops-class.org - Hack the Kernel][91] | 15 weeks | 6 hours/week | algorithms

#### Readings
- **Recommended**: While Hack the Kernel recommends Modern Operating Systems as a textbook, we suggest using [Operating Systems: Three Easy Pieces][92].

### Core theory

**Topics covered**:
`divide and conquer`
`sorting and searching`
`randomized algorithms`
`graph search`
`shortest paths`
`data structures`
`greedy algorithms`
`minimum spanning trees`
`dynamic programming`
`NP-completeness`
`and more`

Process | Courses | Duration | Effort | Prerequisites
 :--: | :-- | :--: | :--: | :--:
:black\_square\_button: | [Data Structures and Algorithms specialization][93] | 6-8 months | 4-8 hours/weeks | Basic knowledge of at least one programming language (C, C++, C#, Haskell, Java, JavaScript, Python2, Python3, Ruby, and Scala): loops, arrays, stacks, recursion. Basic knowledge of mathematics: proof by induction, proof by contradiction.
:black\_square\_button: | [Algorithms][94] | 16 weeks | 4-8 hours/weeks | Learners should know how to program in at least one programming language (like C, Java, or Python); some familiarity with proofs, including proofs by induction and by contradiction; and some discrete probability, like how to compute the probability that a poker hand is a full house. At Stanford, a version of this course is taken by sophomore, junior, and senior-level computer science majors.
:black\_square\_button: | [Algorithms: Design and Analysis, Part I][95] | 8 weeks | 4-8 hours/week | any programming language, Mathematics for Computer Science
:black\_square\_button: | [Algorithms: Design and Analysis, Part II][96] | 8 weeks | 4-8 hours/week | Part I


**Extra stuff**
`some article that you may get more information`
  * [VisualGo][97]
  * [Visualizing Algorithms][98]
  * [Sort Algorithms Animations][99]
  * [Data Structure Visualization][100]
  * [Dynamic programming: from novice to advanced][101]

**MicroMaster Algorithms and Data Structures** (offer by [Edx.org at link][102])



### Core applications

**Topics covered**:
`Agile methodology`
`REST`
`software specifications`
`refactoring`
`relational databases`
`transaction processing`
`data modeling`
`neural networks`
`supervised learning`
`unsupervised learning`
`OpenGL`
`raytracing`
`block ciphers`
`authentication`
`public key encryption`
`and more`

Process | Courses | Duration | Effort | Prerequisites
 :--: | :-- | :--: | :--: | :--:
:black\_square\_button: | [Databases][103] [(more)][104]| 12 weeks | 8-12 hours/week | some programming, basic CS
:black\_square\_button: | [Machine Learning][105]| 11 weeks | 4-6 hours/week | linear algebra
:black\_square\_button: | [Computer Graphics][106]| 6 weeks | 12 hours/week | C++ or Java, linear algebra
:black\_square\_button: | [Cryptography I][107]| 6 weeks | 5-7 hours/week | linear algebra, probability
:black\_square\_button: | [Java Programming and Software Engineering Fundamentals specialization][108] | 6-7 months | 8-12 hours/week | above
:black\_square\_button: | [Software Engineering: Introduction][109] | 6 weeks | 8-10 hours/week | Software Construction - Object-Oriented Design
:black\_square\_button: | [Software Development Capstone Project][110] | 6-7 weeks | 8-10 hours/week | Software Engineering: Introduction

#### Readings
- **Extra read** an open source repo, contain about design pattern topic, that can easily mind wobble [Design Patterns for Humans][111]

**MicroMaster Software Development** (offer by [Edx.org at link][112])


<br/>
<br/>



## Advanced CS

After completing **every required course** in Core CS, students should choose a subset of courses from Advanced CS based on interest.
Not every course from a subcategory needs to be taken.
But students should take *every* course that is relevant to the field they intend to go into.

The Advanced CS study should then end with one of the Specializations under [Advanced applications][113].
A Specialization's Capstone, if taken, may act as the [Final project][114], if permitted by the Honor Code of the course.
If not, or if a student chooses not to take the Capstone, then a separate Final project will need to be done to complete this curriculum.

### Advanced programming

**Topics covered**:
`debugging theory and practice`
`goal-oriented programming`
`GPU programming`
`CUDA`
`parallel computing`
`object-oriented analysis and design`
`UML`
`large-scale software architecture and design`
`and more`

Process | Courses | Duration | Effort | Prerequisites
 :--: | :-- | :--: | :--: | :--:
:black\_square\_button: | [Compilers][115]| 9 weeks | 6-8 hours/week | none
:black\_square\_button: | [Software Debugging][116]| 8 weeks | 6 hours/week | Python, object-oriented programming
:black\_square\_button: | [Software Testing][117] | 4 weeks | 6 hours/week | Python, programming experience
:black\_square\_button: | [LAFF: Programming for Correctness][118] | 7 weeks | 6 hours/week | linear algebra
:black\_square\_button: | [Introduction to Parallel Programming][119] ([alt][120]) | 12 weeks | - | C, algorithms
:black\_square\_button: | [Parallel, Concurrent and Distributed Programming in Java specialization][121] | 12 weeks | 6-8 hours/week | The Specialization is targeted at an audience that is already familiar with sequential programming in Java, including a basic knowledge of Java 8 lambdas.
:black\_square\_button: | [Software Architecture & Design][122]| 8 weeks | 6 hours/week | software engineering in Java
:black\_square\_button: | [Software Design and Architecture specialization][123] | 3 – 5 weeks | 6-8 hours/week | Familiarity with object-oriented programming structures is essential. Basic Java programming knowledge is expected. Assignments and quizzes will require coding in Java. The capstone application will require you to use Android Studio, an integrated development environment.

### Advanced math

**Topics covered**:
`parametric equations`
`polar coordinate systems`
`multivariable integrals`
`multivariable differentials`
`probability theory`
`and more`

Process | Courses | Duration | Effort | Prerequisites
 :--: | :-- | :--: | :--: | :--:
:black\_square\_button: | [Calculus: Parametric Equations and Polar Coordinates][124] | - | - | single-variable calculus (Calculus Two)
:black\_square\_button: | [Multivariable Calculus][125] | 13 weeks | 12 hours/week | Parametric Equations and Polar Coordinates
:black\_square\_button: | [Introduction to Probability - The Science of Uncertainty][126] | 18 weeks | 12 hours/week | Multivariable Calculus
:black\_square\_button: | [Introduction to Probability-part 1]() _(optional)_ | 16 weeks | 6 hours/week | College-level calculus (single-variable & multivariable). Comfort with mathematical reasoning, familiarity with sequences, limits, infinite series, the chain rule, and ordinary or multiple integrals.
:black\_square\_button: | [Introduction to Probability-part 2][128] _(optional)_ | 16 weeks | 6 hours/week | above

### Advanced systems

**Topics covered**:
`digital signaling`
`combinational logic`
`CMOS technologies`
`sequential logic`
`finite state machines`
`processor instruction sets`
`caches`
`pipelining`
`virtualization`
`parallel processing`
`virtual memory`
`synchronization primitives`
`system call interface`
`and more`

Process | Courses | Duration | Effort | Prerequisites
 :--: | :-- | :--: | :--: | :--:
:black\_square\_button: | [Reliable Distributed Systems, Part 1][129] | 5 weeks | 5 hours/week | Scala, intermediate CS
:black\_square\_button: | [Reliable Distributed Systems, Part 2][130] | 5 weeks | 5 hours/week | Part 1
:black\_square\_button: | [Physics II: Electricity and Magnetism, Part 1][131]<sup>1</sup> | 7 weeks | 8-10 hours/week | calculus, basic mechanics
:black\_square\_button: | [Physics II: Electricity and Magnetism, Part 2][132] | 7 weeks | 8-10 hours/week | Electricity and Magnetism, Part 1
:black\_square\_button: | [Computation Structures 1: Digital Circuits][133] | 10 weeks | 6 hours/week | electricity, magnetism
:black\_square\_button: | [Computation Structures 2: Computer Architecture][134] | 10 weeks | 6 hours/week | Computation Structures 1
:black\_square\_button: | [Computation Structures 3: Computer Organization][135] | 10 weeks | 6 hours/week | Computation Structures 2

**<sup>1</sup> Note**:
These courses assume knowledge of basic physics.
([Why?][136])
If you are struggling, you can find a physics MOOC or utilize the materials from Khan Academy:
[Khan Academy - Physics][137]

### Advanced theory

**Topics covered**:
`formal languages`
`Turing machines`
`computability`
`event-driven concurrency`
`automata`
`distributed shared memory`
`consensus algorithms`
`state machine replication`
`computational geometry theory`
`propositional logic`
`relational logic`
`Herbrand logic`
`concept lattices`
`game trees`
`and more`

Process | Courses | Duration | Effort | Prerequisites
 :--: | :-- | :--: | :--: | :--:
:black\_square\_button: | [Introduction to Logic][138] | 10 weeks | 4-8 hours/week | set theory
:black\_square\_button: | [Automata Theory][139] | 8 weeks | 10 hours/week | discrete mathematics, logic, algorithms
:black\_square\_button: | [Computational Geometry][140] | 16 weeks | 8 hours/week | algorithms, C++
:black\_square\_button: | [Introduction to Formal Concept Analysis][141] | 6 weeks | 4-6 hours/week | logic, probability
:black\_square\_button: | [Game Theory][142] | 8 weeks | x hours/week | mathematical thinking, probability, calculus

### Advanced applications

These Coursera Specializations all end with a Capstone project.
Depending on the course, you may be able to utilize the Capstone as your Final Project for this Computer Science curriculum.
Note that doing a Specialization with the Capstone at the end always costs money.
So if you don't wish to spend money or use the Capstone as your Final, it may be possible to take the courses in the Specialization for free by manually searching for them, but not all allow this.

Process | Courses | Duration | Effort | Prerequisites
 :--: | :-- | :--: | :--: | :--:
:black\_square\_button: | [Robotics (Specialization)][143] | 26 weeks | 2-5 hours/week | linear algebra, calculus, programming, probability
:black\_square\_button: | [Data Mining (Specialization)][144] | 30 weeks | 2-5 hours/week | machine learning
:black\_square\_button: | [Big Data (Specialization)][145] | 30 weeks | 3-5 hours/week | none
:black\_square\_button: | [Internet of Things (Specialization)][146] | 30 weeks | 1-5 hours/week | strong programming
:black\_square\_button: | [Cloud Computing (Specialization)][147] | 30 weeks | 2-6 hours/week | C++ programming
:black\_square\_button: | [Full Stack Web Development (Specialization)][148] | 27 weeks | 2-6 hours/week | programming, databases
:black\_square\_button: | [Data Science (Specialization)][149] | 43 weeks | 1-6 hours/week | none
:black\_square\_button: | [Functional Programming in Scala (Specialization)][150] | 29 weeks | 4-5 hours/weeks | One year programming experience



<br/>
<br/>


## Final project

OSS University is **project-focused**.
You are encouraged to do the assignments and exams for each course, but what really matters is whether you can *use* your knowledge to solve a real world problem.

After you've gotten through all of Core CS and the parts of Advanced CS relevant to you, you should think about a problem that you can solve using the knowledge you've acquired.
Not only does real project work look great on a resume, the project will *validate* and *consolidate* your knowledge.
You can create something entirely new, or you can find an existing project that needs help via websites like
[CodeTriage][151]
or
[First Timers Only][152].

Another option is using the Capstone project from taking one of the Specializations in [Advanced applications][153];
whether or not this makes sense depends on the course, the project, and whether or not the course's Honor Code permits you to display your work publicly.
In some cases, it may not be permitted;
do **not** violate your course's Honor Code!

Put the OSSU-CS badge in the README of your repository!
[![Open Source Society University - Computer Science][image-2]][154]

- Markdown: `[![Open Source Society University - Computer Science](https://img.shields.io/badge/OSSU-computer--science-blue.svg)](https://github.com/ossu/computer-science)`
- HTML: `<a href="https://github.com/ossu/computer-science"><img alt="Open Source Society University - Computer Science" src="https://img.shields.io/badge/OSSU-computer--science-blue.svg"></a>`

### Evaluation

Upon completing your final project, submit your project's information to [PROJECTS][155]
via a pull request and use our [community][156] channels to announce it to your fellow students.

Your peers and mentors from OSSU will then informally evaluate your project.
You will not be "graded" in the traditional sense — everyone has their own measurements for what they consider a success.
The purpose of the evaluation is to act as your first announcement to the world that you are a computer scientist,
and to get experience listening to feedback — both positive and negative — and taking it in stride.

The final project evaluation has a second purpose: to evaluate whether OSSU,
through its community and curriculum, is successful in its mission to guide independent learners in obtaining a world-class computer science education.

### Cooperative work

You can create this project alone or with other students!
**We love cooperative work**!
Use our [channels][157] to communicate with other fellows to combine and create new projects!

### Which programming languages should I use?

My friend, here is the best part of liberty!
You can use **any** language that you want to complete the final project.

The important thing is to **internalize** the core concepts and to be able to use them with whatever tool (programming language) that you wish.



<br/>
<br/>


## Pro CS

After completing the requirements of the curriculum above, you will have completed the equivalent of a full bachelor's degree in Computer Science, or quite close to one.
You can stop in the Advanced CS section, but the next step to completing your studies is to develop skills and knowledge in a specific domain.
Many of these courses are graduate-level.

Choose one or more of the following **specializations**:
- [Mastering Software Development in R Specialization][158] by Johns Hopkins University
- [Artificial Intelligence Engineer Nanodegree][159] by IBM, Amazon, and Didi
- [Machine Learning Engineer Nanodegree][160] by kaggle
- [Cybersecurity MicroMasters][161] by the Rochester Institute of Technology
- [Cybersecurity specialization list][162] in Coursera
- [Android Developer Nanodegree][163] by Google
- [Software Product Management specialization][164] by Coursera
- [Agile Development specialization][165] by Coursera

These aren't the only specializations you can choose. Check the following websites for **more options**:
- edX: [xSeries][166]
- Coursera: [Specializations][167]
- Udacity: [Nanodegree][168]

### Where to go next?

- Look for a job as a developer!
- Check out the [readings][169] for classic books you can read that will sharpen your skills and expand your knowledge.
- Join a local developer meetup (e.g. via [meetup.com][170]).
- Pay attention to emerging technologies in the world of software development:
  + Explore the **actor model** through [Elixir][171], a new functional programming language for the web based on the battle-tested Erlang Virtual Machine!
  + Explore **borrowing and lifetimes** through [Rust][172], a systems language which achieves memory- and thread-safety without a garbage collector!
  + Explore **dependent type systems** through [Idris][173], a new Haskell-inspired language with unprecedented support for type-driven development.

![keep learning][image-3]



<br/>
<br/>


# Code of conduct
[OSSU's code of conduct][174].

# Community

- Subscribe to our [newsletter][175].
- Use our [forum][176] if you need some help.
- You can also interact through [GitHub issues][177].
- We also have a chat room! [![Join the chat at https://gitter.im/open-source-society/computer-science][image-4]][178]
- Add **Open Source Society University** to your [Linkedin][179] and [Facebook][180] profile!

> **PS**: A forum is an ideal way to interact with other students as we do not lose important discussions, which usually occur in communication via chat apps.
**Please use our forum for important discussions**.

## :chart\_with\_upwards\_trend: How to show your progress

1. Create an account in [Trello][181].
1. Copy [this][182] board to your personal account.
See how to copy a board [here][183].

Now that you have a copy of our official board, you just need to pass the cards to the `Doing` column or `Done` column as you progress in your study.

We also have **labels** to help you have more control through the process.
The meaning of each of these labels is:

- `Main Curriculum`: cards with that label represent courses that are listed in our curriculum.
- `Extra Resources`: cards with that label represent courses that was added by the student.
- `Doing`: cards with that label represent courses the student is current doing.
- `Done`: cards with that label represent courses finished by the student.
Those cards should also have the link for at least one project/article built with the knowledge acquired in such course.
- `Section`: cards with that label represent the section that we have in our curriculum.
Those cards with the `Section` label are only to help the organization of the Done column.
You should put the *Course's cards* below its respective *Section's card*.

The intention of this board is to provide our students a way to track their progress, and also the ability to show their progress through a public page for friends, family, employers, etc.
You can change the status of your board to be *public* or *private*.

## Team

* **Curriculum Founders**: [Eric Douglas][184]
* **Curriculum Maintainers**: [Eric Douglas][185] and [hanjiexi][186]
* **Contributors**: [contributors][187]

# References

- [Google - Guide for Technical Development][188]
- [Coursera][189]
- [edX][190]
- [Udacity][191]
- [Stanford University][192]
- [Carnegie Mellon University: Computer Science Major Requirements][193]
- [MIT Open Courseware][194] - [MIT Department: Bachelor of Computer Science and Engineering][195]

- [Coding Interview University][196]
- [Teach Yourself Computer Science][197]
- [Obtaining a Thorough CS Background Online][198]

[1]:	https://github.com/ossu/computer-science
[2]:	#summary
[3]:	#about
[4]:	#motivation--preparation
[5]:	#curriculum
[6]:	#prerequisites
[7]:	#introduction-to-computer-science
[8]:	#core-cs
[9]:	#advanced-cs
[10]:	#final-project
[11]:	#pro-cs
[12]:	#code-of-conduct
[13]:	#community
[14]:	#how-to-show-your-progress
[15]:	#team
[16]:	#references
[17]:	REQUIREMENTS.md
[18]:	extras/courses.md
[19]:	extras/readings.md
[20]:	https://learner.coursera.help/hc/en-us/articles/209819033-Apply-for-Financial-Aid
[21]:	https://github.com/ossu/cohorts
[22]:	https://en.wikipedia.org/wiki/Topological_sorting
[23]:	CONTRIBUTING.md
[24]:	FAQ.md
[25]:	#community
[26]:	https://www.scotthyoung.com/blog/myprojects/mit-challenge-2/
[27]:	https://www.coursera.org/learn/learning-how-to-learn
[28]:	CHANGELOG.md
[29]:	#prerequisites
[30]:	#introduction-to-computer-science
[31]:	#core-cs
[32]:	#core-programming
[33]:	#core-math
[34]:	#core-systems
[35]:	#core-theory
[36]:	#core-applications
[37]:	#advanced-cs
[38]:	#advanced-programming
[39]:	#advanced-math
[40]:	#advanced-systems
[41]:	#advanced-theory
[42]:	#advanced-applications
[43]:	#final-project
[44]:	#pro-cs
[45]:	#core-cs
[46]:	#advanced-cs
[47]:	#advanced-systems
[48]:	FAQ.md#why-do-you-recommend-skipping-the-second-half-of-cs50
[49]:	https://www.edx.org/course/introduction-computer-science-harvardx-cs50x#!
[50]:	https://cs50.harvard.edu/
[51]:	https://www.edx.org/course/introduction-computer-science-mitx-6-00-1x-10
[52]:	https://www.edx.org/course/introduction-computational-thinking-data-mitx-6-00-2x-6
[53]:	https://www.coursera.org/specializations/computer-fundamentals
[54]:	https://www.coursera.org/specializations/introduction-scripting-in-python
[55]:	https://www.edx.org/course/how-code-simple-data-ubcx-htc1x
[56]:	https://www.edx.org/course/how-code-complex-data-ubcx-htc2x
[57]:	https://www.edx.org/course/software-construction-data-abstraction-ubcx-softconst1x
[58]:	https://www.edx.org/course/software-construction-object-oriented-ubcx-softconst2x
[59]:	https://www.coursera.org/learn/programming-languages
[60]:	https://www.coursera.org/learn/programming-languages-part-b
[61]:	https://www.coursera.org/learn/programming-languages-part-c
[62]:	http://learnyouahaskell.com/
[63]:	http://haskellbook.com/
[64]:	http://lpn.swi-prolog.org/lpnpage.php?pageid=top
[65]:	https://www.khanacademy.org/math
[66]:	https://www.coursera.org/learn/pre-calculus
[67]:	https://www.coursera.org/learn/trigonometry
[68]:	https://www.edx.org/course/precalculus-asux-mat170x
[69]:	https://www.edx.org/course/pre-university-calculus-delftx-calc001x-2
[70]:	https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab
[71]:	https://www.edx.org/course/linear-algebra-foundations-to-frontiers#!
[72]:	http://ulaff.net/
[73]:	https://www.coursera.org/learn/calculus1
[74]:	https://mooculus.osu.edu/
[75]:	https://www.coursera.org/learn/advanced-calculus
[76]:	https://www.edx.org/course/calculus-1a-differentiation-mitx-18-01-1x-0
[77]:	https://www.edx.org/course/introduction-differential-equations-mitx-18-031x
[78]:	https://www.edx.org/course/differential-equations-2x2-systems-mitx-18-032x
[80]:	https://www.edx.org/course/calculus-1b-integration-mitx-18-01-2x-0
[81]:	https://www.edx.org/course/calculus-1c-coordinate-systems-infinite-mitx-18-01-3x-0
[82]:	https://www.edx.org/course/calculus-applied-harvardx-calcapl1x
[83]:	https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/index.htm
[84]:	https://www.coursera.org/specializations/discrete-mathematics
[85]:	https://www.coursera.org/learn/build-a-computer
[86]:	http://www.nand2tetris.org/
[87]:	https://www.coursera.org/learn/nand2tetris2
[88]:	https://user-images.githubusercontent.com/2046800/35426340-f6ce6358-026a-11e8-8bbb-4e95ac36b1d7.png
[89]:	https://www.youtube.com/channel/UCnoYy1k6I5gLIxhlNiStrdQ
[90]:	https://lagunita.stanford.edu/courses/Engineering/Networking-SP/SelfPaced/about
[91]:	https://www.ops-class.org/
[92]:	http://pages.cs.wisc.edu/~remzi/OSTEP/
[93]:	https://www.coursera.org/specializations/data-structures-algorithms
[94]:	https://www.coursera.org/specializations/algorithms
[95]:	https://lagunita.stanford.edu/courses/course-v1:Engineering+Algorithms1+SelfPaced/about
[96]:	https://lagunita.stanford.edu/courses/course-v1:Engineering+Algorithms2+SelfPaced/about
[97]:	https://visualgo.net/en
[98]:	https://bost.ocks.org/mike/algorithms/
[99]:	https://www.toptal.com/developers/sorting-algorithms
[100]:	https://www.cs.usfca.edu/~galles/visualization/Algorithms.html
[101]:	https://www.topcoder.com/community/data-science/data-science-tutorials/dynamic-programming-from-novice-to-advanced/
[102]:	https://www.edx.org/micromasters/ucsandiegox-algorithms-and-data-structures
[103]:	https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/about
[104]:	https://github.com/luuductrung1234/computer-science/blob/master/extras/db-courses.md#course
[105]:	https://www.coursera.org/learn/machine-learning
[106]:	https://www.edx.org/course/computer-graphics-uc-san-diegox-cse167x
[107]:	https://www.coursera.org/course/crypto
[108]:	https://www.coursera.org/specializations/java-programming
[109]:	https://www.edx.org/course/software-engineering-introduction-ubcx-softeng1x
[110]:	https://www.edx.org/course/software-development-capstone-project-ubcx-softengprjx
[111]:	https://github.com/kamranahmedse/design-patterns-for-humans#creational-design-patterns
[112]:	https://www.edx.org/micromasters/software-development
[113]:	#advanced-applications
[114]:	#final-project
[115]:	https://lagunita.stanford.edu/courses/Engineering/Compilers/Fall2014/about
[116]:	https://www.udacity.com/course/software-debugging--cs259
[117]:	https://www.udacity.com/course/software-testing--cs258
[118]:	https://www.edx.org/course/laff-programming-correctness-utaustinx-ut-p4c-14-01x
[119]:	https://www.udacity.com/course/intro-to-parallel-programming--cs344
[120]:	https://www.youtube.com/playlist?list=PLGvfHSgImk4aweyWlhBXNF6XISY3um82_
[121]:	https://www.coursera.org/specializations/java-programming
[122]:	https://www.udacity.com/course/software-architecture-design--ud821
[123]:	https://www.coursera.org/specializations/software-design-architecture
[124]:	https://ocw.mit.edu/courses/mathematics/18-01sc-single-variable-calculus-fall-2010/unit-4-techniques-of-integration/part-c-parametric-equations-and-polar-coordinates/
[125]:	https://ocw.mit.edu/courses/mathematics/18-02sc-multivariable-calculus-fall-2010/index.htm
[126]:	https://www.edx.org/course/introduction-probability-science-mitx-6-041x-2
[128]:	https://www.edx.org/course/introduction-to-probability-part-2-inference-processes
[129]:	https://www.edx.org/course/reliable-distributed-algorithms-part-1-kthx-id2203-1x
[130]:	https://www.edx.org/course/reliable-distributed-algorithms-part-2-kthx-id2203-2x
[131]:	https://www.edx.org/course/electricity-magnetism-part-1-ricex-phys102-1x-0
[132]:	https://www.edx.org/course/electricity-magnetism-part-2-ricex-phys102-2x-0
[133]:	https://www.edx.org/course/computation-structures-part-1-digital-mitx-6-004-1x-0
[134]:	https://www.edx.org/course/computation-structures-2-computer-mitx-6-004-2x
[135]:	https://www.edx.org/course/computation-structures-3-computer-mitx-6-004-3x-0
[136]:	FAQ.md#why-is-the-curriculum-missing-some-pre-requisites
[137]:	https://www.khanacademy.org/science/physics
[138]:	https://www.coursera.org/learn/logic-introduction
[139]:	https://lagunita.stanford.edu/courses/course-v1:ComputerScience+Automata+Fall2016/about
[140]:	https://www.edx.org/course/computational-geometry-tsinghuax-70240183x
[141]:	https://www.coursera.org/learn/formal-concept-analysis
[142]:	https://www.coursera.org/learn/game-theory-1
[143]:	https://www.coursera.org/specializations/robotics
[144]:	https://www.coursera.org/specializations/data-mining
[145]:	https://www.coursera.org/specializations/big-data
[146]:	https://www.coursera.org/specializations/internet-of-things
[147]:	https://www.coursera.org/specializations/cloud-computing
[148]:	https://www.coursera.org/specializations/full-stack
[149]:	https://www.coursera.org/specializations/jhu-data-science
[150]:	https://www.coursera.org/specializations/scala
[151]:	https://www.codetriage.com/
[152]:	http://www.firsttimersonly.com/
[153]:	#advanced-applications
[154]:	https://github.com/ossu/computer-science
[155]:	PROJECTS.md
[156]:	#community
[157]:	#community
[158]:	https://www.coursera.org/specializations/r
[159]:	https://www.udacity.com/ai
[160]:	https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009
[161]:	https://www.edx.org/micromasters/ritx-cybersecurity
[162]:	https://www.coursera.org/browse/computer-science/computer-security-and-networks?languages=en
[163]:	https://www.udacity.com/course/android-developer-nanodegree-by-google--nd801
[164]:	https://www.coursera.org/specializations/product-management
[165]:	https://www.coursera.org/specializations/agile-development
[166]:	https://www.edx.org/xseries
[167]:	https://www.coursera.org/specializations
[168]:	https://www.udacity.com/nanodegree
[169]:	extras/readings.md
[170]:	https://www.meetup.com/
[171]:	http://elixir-lang.org/
[172]:	https://www.rust-lang.org/
[173]:	https://www.idris-lang.org/
[174]:	https://github.com/ossu/code-of-conduct
[175]:	https://tinyletter.com/ossu
[176]:	https://github.com/ossu/forum
[177]:	https://github.com/ossu/computer-science/issues
[178]:	https://gitter.im/open-source-society/computer-science?utm_campaign=pr-badge&utm_content=badge&utm_medium=badge&utm_source=badge
[179]:	https://www.linkedin.com/school/11272443/
[180]:	https://www.facebook.com/ossuniversity
[181]:	https://trello.com/
[182]:	https://trello.com/b/9DPXYv5f
[183]:	http://blog.trello.com/you-can-copy-boards-now-finally/
[184]:	https://github.com/ericdouglas
[185]:	https://github.com/ericdouglas
[186]:	https://github.com/hanjiexi
[187]:	https://github.com/ossu/computer-science/graphs/contributors
[188]:	https://www.google.com/about/careers/students/guide-to-technical-development.html
[189]:	https://www.coursera.org/
[190]:	https://www.edx.org
[191]:	https://www.udacity.com/
[192]:	https://lagunita.stanford.edu/
[193]:	https://www.csd.cs.cmu.edu/academics/undergraduate/requirements
[194]:	http://ocw.mit.edu/courses/#electrical-engineering-and-computer-science
[195]:	http://catalog.mit.edu/degree-charts/computer-science-engineering-course-6-3/
[196]:	https://github.com/jwasham/coding-interview-university
[197]:	https://teachyourselfcs.com/
[198]:	http://spin.atomicobject.com/2015/05/15/obtaining-thorough-cs-background-online/

[image-1]:	http://i.imgur.com/kYYCXtC.png
[image-2]:	https://img.shields.io/badge/OSSU-computer--science-blue.svg
[image-3]:	http://i.imgur.com/REQK0VU.jpg
[image-4]:	https://badges.gitter.im/Join%20Chat.svg
