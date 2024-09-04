---
title: "String Manipulation via Boolean Automata [College Student Research Creativity Award]"
date: 2020-01-01
permalink: /projects/sba
excerpt_separator: <!--more-->
toc: true
tags:
  - National Taiwan University, Taiwan
  - Applied Logic and Computation Lab (Prof. Jie-Hong R. Jiang)
  - EDA
---

* Perform regular language operations via Boolean automata representation
<!--more-->
<!-- --- -->
<!-- title: "String Manipulation via Boolean Automata [College Student Research Creativity Award]"
collection: EDA-related
type: "EDA-related"
permalink: /projects/sba
venue: "Applied Logic and Computation Lab (Prof. Jie-Hong R. Jiang)"
date: 2020-01-01
location: "National Taiwan University, Taiwan"
--- -->

<!-- [More information here]() -->
As web applications are applied in the safety-critical area, the security issue of web applications becomes crucial. By formal string analysis, we can effectively prevent security vulnerabilities caused by string manipulation mistakes. However, prior automata-based string analysis approaches suffer from the state explosion problem. More specifically, deterministic finite automata (DFA)-based methods require subset construction while doing language concatenation, leading to state number exponential grow up. Although nondeterministic finite automata (NFA)-based methods crafty avoid the state explosion problem in DFA approaches by the advantage of nondeterminism, subset construction is also required at the step of language complement. Therefore, devising an efficient approach to do all string operation is desired. In this report, we propose a new Boolean automata-based approach to implement the most common string operation without the expensive cost. Boolean automata are the more succinct representation of formal language than DFA and NFA. By introducing nondeterminism to Boolean automata, complicated string operations such as concatenation and replacement can be implemented in polynomial time.