---
layout: post
title: Preference
description:  An Agent's expression of predilection between two __World States__. __Preference__ may favour either __State__, or may reflect indifference. __Preference__ is not intrinsic, and cannot be specified in the absence of an Agent. 
---

Given an Agent's __Preference__ system $$ s $$, __Preference__ is formulated as $$
\begin{equation}
V(s, w_1, w_2) = \left\{
\begin{array}{cl}
0 & w_1 \ {\rm and} \ w_2 \ {\rm of \ equal \ value}\\
1 & w_1 \ {\rm of \ greater \ value}\\
-1 & w_2 \ {\rm of \ greater \ value}
\end{array}
\right.
\end{equation}
$$