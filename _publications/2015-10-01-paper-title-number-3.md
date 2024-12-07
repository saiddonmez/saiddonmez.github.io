---
title: "Logit-Q dynamics for efficient learning in stochastic teams"
collection: publications
permalink: /publication/logit-q-dynamics-for-efficient-learning
excerpt: 'This paper presents a new family of logit-Q dynamics for efficient learning in stochastic games
by combining the log-linear learning (also known as logit dynamics) for the repeated play
of normal-form games with Q-learning for unknown Markov decision processes.'
date: 2024-01-01
venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/2302.09806'
citation: 
---

We present a new family of logit-Q dynamics for efficient learning in stochastic games
by combining the log-linear learning (also known as logit dynamics) for the repeated play
of normal-form games with Q-learning for unknown Markov decision processes within the
auxiliary stage-game framework. In this framework, we view stochastic games as agents
repeatedly playing some stage game associated with the current state of the underlying game
while the agents’ Q-functions determine the payoffs of these stage games. We show that the
logit-Q dynamics presented reach (near) efficient equilibrium in stochastic teams with unknown
dynamics and quantify the approximation error. We also show the rationality of the logitQ dynamics against agents following pure stationary strategies and the convergence of the
dynamics in stochastic games where the stage-payoffs induce potential games, yet only a single
agent controls the state transitions beyond stochastic teams. The key idea is to approximate the
dynamics with a fictional scenario where the Q-function estimates are stationary over epochs
whose lengths grow at a sufficiently slow rate. We then couple the dynamics in the main and
fictional scenarios to show that these two scenarios become more and more similar across epochs
due to the vanishing step size and growing epoch lengths
