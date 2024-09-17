---
title: 'CS476: Program Verification'
subtitle: Fall 2024
fontsize: 16px
---

-  **Time:** Tuesday and Thursday, 9:30-10:45
-  **Professor:** [José Meseguer](http://formal.cs.illinois.edu/meseguer/)
   (email: <meseguer@illinois.edu>)
-  **Office hours:***  10:50-12:00 at Siebel 2108, or by
   appointment requested after each lecture.  Any consultations should be
   made during office hours.



Topic List
----------

-   Algebraic specification of declarative deterministic programs
-   Inductive first-order logic and inductive theorem proving
-   Formal verification of declarative functional programs
-   Rewriting logic specification of declarative concurrent programs
-   Modal and temporal logics
-   Model checking verification of modal and temporal logic properies
     of declarative concurrent programs
-   Rewriting logic semantics of imperative concurrent programs
-   Model checking verification of imperative concurrent programs
-   Narrowing-based model checking verification of modal and temporal logic
     properties of infinite-state declarative concurrent programs


Course Work, Policies and Procedures {#grading}
------------------------------------

Students taking the course will be expected to:

-   **Participate actively** and regularly in the course.
-   Present answers to **biweekly homework assignments** solved
    **individually**. Although student interaction and cooperation is
    encouraged, this **excludes** any communication on how to solve
    posted homework assignments, including the comprehensive one (see below).
    Communication on how to solve homework would constitute a
    serious violation of the honor code.
-   Present answers to a **midterm exam** at the classroom during the normal 
     lecture time (9:30 to 10:45) on Thursday October 17.  Students are encouraged
     to be at the classroom a few minutes before the exam, so that the exam
     can begin on time and they can have the full 75 minutes to write their answers.
-   A **comprehensive homework assignment** at the end of the course.
-   (if the course is taken for 4 units) Develop a **term project**,
    either individually or as part of a small group of students.

**Grading.**

-   The regularity in active participation will contribute 10% to the final grade.
-   Each problem on each  biweekly homework assignment will be worth 10 points, and
    the biweekly homeworks all together will be worth 50% of the grade.
-   Late homework will receive a 0%.
-   The midterm exam will be worth 20% of the grade.
-   The comprehensive homework assignment will be worth 20% of the grade.
-   There will be no final exam.
-   If you are taking the class for 4 credits, then there will also be a final
    project for the course. The final project must be turned in by the assigned
    final date before a grade for the class will be issued.

Reading Materials
-----------------


-   [(STACS) Set Theory and Algebra in Computer Science].
-   [Peter Olveczky\'s book Formal Modeling and Analysis of Distributed
    Systems].
-   [All About Maude]
-   [Programming and Symbolic Computation in Maude].
-   [Maude Termination Assistant]. The MTA tool, its manual, and a collection of
    examples can be found on the [MTA website].

  [(STACS) Set Theory and Algebra in Computer Science]: readings/STACS.pdf
  [Peter Olveczky\'s book Formal Modeling and Analysis of Distributed Systems]:
    https://vufind.carli.illinois.edu/vf-uiu/Record/uiu_8560680
  [Maude Manual]: https://maude.cs.illinois.edu/w/images/e/e9/Maude34manual.pdf
  [All About Maude]: https://vufind.carli.illinois.edu/vf-uiu/Record/uiu_5675801
  [Programming and Symbolic Computation in Maude]: readings/maude-jlamp.pdf
  [Maude Termination Assistant]: readings/MTA.pdf
  [MTA website]: http://maude.cs.illinois.edu/tools/mta

Lectures
--------

### Lecture 1 (27th Aug)

* [Slides](lectures/pv1-slides.pdf)

### Lecture 2 (29th Aug)

* [Slides](lectures/pv2-slides.pdf)

### Lecture 3 (3rd Sep)

* [Slides](lectures/pv3-slides.pdf)

### Lecture 4 (5th Sept)

* [Slides](lectures/pv4-slides.pdf)

### Lecture 5 (10th Sept)

* [Slides](lectures/pv5-slides.pdf)

### Lecture 6 (12th Sept)

* [Slides](lectures/pv6-slides-24.pdf)

### Lecture 7 (17th Sept)

* [Slides](lectures/pv7-slides-24.pdf)

### Lecture 8 (19th Sept)

* [Slides](lectures/pv8-slides-24.pdf)


Homework
--------

When submitting homework please make sure:

1.  All attachments should start with `cs476-hwN-<netid>`.

    For example, `cs476-hw2-wuxytan7.pdf`, or `cs476-hw2-wuxytan7-nat-list.maude`.

    :::warning
    From HW2 onward, two points will be deducted if you do not use this format.
    It may be hard to find your assignment if you don't use this format.

    Make sure you use hypens and not underscores.
    :::

2.  Place your name and netid in the title or header of the PDF.
    This is to ensure that your homework doesn't get mixed up with someone else's.

### HW1 (Due 10th Sept)

* [Homework 1](homework/hw#1-24.pdf)

### HW2 (Due 24th Sept)

* [Homework 2](homework/hw#2-24.pdf)
 
  [int-arith-skeleton.maude](int-arith-skeleton.maude)

  [list-funs-skeleton.maude](list-funs-skeleton.maude)

Tools used
----------

### Maude and Maude tools

Maude will be the primary tool used in this course.  Several other
tools/libraries written in Maude will also be used.  Instructions
about them will appear at or before the time when they are
used in some lectures.

The current
version
is Maude 3.4.  Maude executables for both Linux and Mac OS  can
be downloaded from the github release page
and installed as per instructions at [the Maude wiki](https://maude.cs.illinois.edu/wiki/Maude_download_and_installation).

#### Instructions for usage on EWS (Maude 3.1)

The EWS machines have an older version of glibc, so we must use Maude 3.1
instead of the latest available version.
Below are instructions to download and install that version.

```
$ wget http://maude.cs.illinois.edu/w/images/3/38/Maude-3.1-linux.zip
$ unzip Maude-3.1-linux.zip
$ cd maude-3.1/
$ ./maude.linux64
./maude.linux64: /lib64/libtinfo.so.5: no version information available (required by ./maude.linux64)
             \||||||||||||||||||/
           --- Welcome to Maude ---
             /||||||||||||||||||\
         Maude 3.1 built: Oct 12 2020 20:12:31
         Copyright 1997-2020 SRI International
           Mon Aug 29 11:15:24 2022
Maude>
```

