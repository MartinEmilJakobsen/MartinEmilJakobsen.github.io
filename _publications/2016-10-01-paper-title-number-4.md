---
title: "Structure Learning for Directed Trees"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'We propose a method to consistently estimate the underlying causal structure of non-linear additive noise directed tree models. Furthermore, we propose a procedure to test causal substructure hypotheses.'
date: 2022-02-02
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2108.08871'
citation: 'Martin Emil Jakobsen,  Rajen D. Shah, Peter Bühlmann and Jonas Peters (2021). "Structure Learning for Directed Trees" <i> arXiv:2108.08871</i>'
---
<i>Summary:</i> Knowing the causal structure of a system is of fundamental interest in many areas of science and can aid the design of prediction algorithms that work well under manipulations to the system. The causal structure becomes identifiable from the observational distribution under certain restrictions. To learn the structure from data, score-based methods evaluate different graphs according to the quality of their fits. However, for large nonlinear models, these rely on heuristic optimization approaches with no general guarantees of recovering the true causal structure. In this paper, we consider structure learning of directed trees. We propose a fast and scalable method based on Chu-Liu-Edmonds' algorithm we call causal additive trees (CAT). For the case of Gaussian errors, we prove consistency in an asymptotic regime with a vanishing identifiability gap. We also introduce a method for testing substructure hypotheses with asymptotic family-wise error rate control that is valid post-selection and in unidentified settings. Furthermore, we study the identifiability gap, which quantifies how much better the true causal model fits the observational distribution, and prove that it is lower bounded by local properties of the causal model. Simulation studies demonstrate the favorable performance of CAT compared to competing structure learning methods.

[Download paper here](https://arxiv.org/abs/2108.08871)
