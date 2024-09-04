---
title: "Language Equation Solving via Reversed Boolean Automata representation [IWLS 2022][ICCAD 2022]"
date: 2021-11-01
permalink: /projects/lba
excerpt_separator: <!--more-->
toc: true
tags:
  - National Taiwan University, Taiwan
  - Applied Logic and Computation Lab (Prof. Jie-Hong R. Jiang)
  - EDA
---


<!-- ---
title: "Language Equation Solving via Reversed Boolean Automata representation [IWLS 2022][ICCAD 2022]"
collection: EDA-related
type: "EDA-related"
permalink: /projects/lba
venue: "Applied Logic and Computation Lab (Prof. Jie-Hong R. Jiang)"
date: 2021-11-01
location: "National Taiwan University, Taiwan"
--- -->

* Solve syncornous composition synthesis via reversed Boolean automata and reversed alternating Boolean automata
<!--more-->

<!-- [More information here]() -->
Language equations are a powerful tool for compositional synthesis, modeled as the unknown component problem.
Given a (sequential) system specification $S$ and a fixed component $F$, we are asked to synthesize an unknown component $X$ such that whose composition with $F$ fulfills $S$.
The synthesis of $X$ can be formulated with language equation solving.
Although prior work exploits partitioned representation for effective finite automata manipulation, it remains challenging to solve language equations involving a large number of states.
In this work, we propose variants of Boolean automata as the underlying succinct representation for regular languages.
They admit logic circuit manipulation and extend the scalability for solving language equations. 
Experimental results demonstrate the superiority of our method to the state of the art in solving the unknown component problem.

