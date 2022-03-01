---
title: "A causal framework for distribution generalization"
collection: publications
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'We investigate the problem of out-of-distribution prediction from a causal model perspective where perturbations of the test-data distribution arise from interventions. We analyze the connection between the best predictive model and causal model. Finally, we propose a non-parametric causal effect estimator'
date: 2021-07-07
venue: 'IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)'
paperurl: 'https://doi.org/10.1109/TPAMI.2021.3094760'
citation: 'Rune Christiansen, Niklas Pfister, Martin Emil Jakobsen, Nicola Gnecco, and Jonas Peters (2021). "A causal framework for distribution generalization" <i>IEEE Transactions on Pattern Analysis and Machine Intelligence</i>. Forthcoming.'
---
<i>Abstract:</i> We consider the problem of predicting a response Y from a set of covariates X when test- and training distributions differ. Since such differences may have causal explanations, we consider test distributions that emerge from interventions in a structural causal model, and focus on minimizing the worst-case risk. Causal regression models, which regress the response on its direct causes, remain unchanged under arbitrary interventions on the covariates, but they are not always optimal in the above sense. For example, for linear models and bounded interventions, alternative solutions have been shown to be minimax prediction optimal. We introduce the formal framework of distribution generalization that allows us to analyze the above problem in partially observed nonlinear models for both direct interventions on X and interventions that occur indirectly via exogenous variables A . It takes into account that, in practice, minimax solutions need to be identified from data. Our framework allows us to characterize under which class of interventions the causal function is minimax optimal. We prove sufficient conditions for distribution generalization and present corresponding impossibility results. We propose a practical method, NILE, that achieves distribution generalization in a nonlinear IV setting with linear extrapolation. We prove consistency and present empirical results.

[Download paper here](https://doi.org/10.1109/TPAMI.2021.3094760)
