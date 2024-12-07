---
title: "Team-Fictitious Play for Reaching Team-Nash
Equilibrium in Multi-team Games"
collection: publications
category: manuscripts
permalink: /publication/Team-Fictitious-Play-for-Reaching-Team-Nash-Equilibrium
excerpt: 'This paper presents a simple multi-team learning algorithm that predicts the emerging team behavior without explicit communication of self-interested agents in multi-team zero-sum networked games.'
date: 2024-01-01
venue: 'NeurIPS 2024'
paperurl: 'https://arxiv.org/abs/2402.02147'
citation: 
---

Multi-team games, prevalent in robotics and resource management, involve team
members striving for a joint best response against other teams. Team-Nash equilibrium
(TNE) predicts the outcomes of such coordinated interactions. However, can
teams of self-interested agents reach TNE? We introduce Team-FP, a new variant
of fictitious play where agents respond to the last actions of team members and the
beliefs formed about other teams with some inertia in action updates. This design is
essential in team coordination beyond the classical fictitious play dynamics. We focus
on zero-sum potential team games (ZSPTGs) where teams can interact pairwise
while the team members do not necessarily have identical payoffs. We show that
Team-FP reaches near TNE in ZSPTGs with a quantifiable error bound. We extend
Team-FP dynamics to multi-team Markov games for model-based and modelfree
cases. The convergence analysis tackles the challenge of non-stationarity
induced by evolving opponent strategies based on the optimal coupling lemma and
stochastic differential inclusion approximation methods. Our work strengthens
the foundation for using TNE to predict the behavior of decentralized teams and
offers a practical rule for team learning in multi-team environments. We provide
extensive simulations of Team-FP dynamics and compare its performance with
other independent algorithms, including explicit collaboration with FP. We further
explore how different parameters impact the speed of convergence.
