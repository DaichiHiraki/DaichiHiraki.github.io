---
title: "Unified mixture sampler for state-space models: Application to stochastic conditional duration models"
collection: publications
category: preprint
permalink: /publication/2026-04-06-unified-mixture-sampler-for-state-space-models application-to-stochastic-conditional-duration-models
excerpt: 'We propose a unified mixture sampler (UMS) that provides a universal estimation framework for nonlinear state-space models with "exp-exp" likelihood kernels.'
date: 2026-04-06
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2604.04517'
# citation: 'Hiraki et al. (2024). &quot;State-Space Modeling of Shape-constrained Functional Time Series.&quot; <i>arXiv preprint arXiv:2404.07586</i>.'
---

## Abstract
We propose a unified mixture sampler (UMS) that provides a universal estimation framework for nonlinear state-space models with "exp-exp" likelihood kernels. Unlike existing methods that require deriving new mixture approximations for each specific distribution, our approach dynamically adapts the standard ten-component mixture from Omori et al. (2007) through a deterministic re-centering and rescaling algorithm. Applying this to the stochastic conditional duration (SCD) model, we demonstrate that the proposed sampler can efficiently handle unknown shape parameters - such as those in Weibull or Gamma distributions - by updating mixture components near-instantaneously during MCMC iterations. The UMS not only simplifies implementation but also ensures exact inference via a lightweight Metropolis-Hastings step. Numerical examples show that our method substantially outperforms the conventional slice sampling approach, significantly reducing autocorrelation in MCMC samples while maintaining high computational efficiency. This unified framework encompasses a wide range of applications, including logit, Poisson, and various SCD model specifications, providing a highly efficient alternative to model-specific samplers.
[Download paper here](https://arxiv.org/abs/2604.04517)
