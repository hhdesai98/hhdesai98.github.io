---
title: "MCMC Variable Selection"
excerpt: "Univariate Logistic Regression Model Selection"
collection: projects
---

See my github page [here](https://github.com/hhdesai98/mcmc_variable_selection)

# Logistic Variable MCMC Selection

This repo contains an MCMC variable selection algorithm for univariate logistic regression with normal priors. The dataset contains 60 covariates and a response variable y. The parallelR22.cpp file contains the algorithm itself, which will select variables and rank models according to their Marginal Likelihood (calculated through monte carlo integration and laplace approximations).  


