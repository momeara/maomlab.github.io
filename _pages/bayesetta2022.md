---
title: "Maom Lab - Bayesetta"
layout: textlay
excerpt: "Maom Lab -- Bayesetta"
sitemap: false
permalink: /bayesetta/
---
#Bayesetta Workshop

##Bayesian Statistical Modeling Workshop for Rosetta-based Modeling

###Workshop Goals
An integral part of protein structural modeling with Rosetta is evaluating the quality of predictions against experimental observations. The community effort to develop Scientific Benchmarks has been instrumental in tracking and measuring modeling progress. However, due to the complexity and uncertainty in both the model predictions and the biochemical data, it can be challenging for researchers from both biochemical and computational researchers without a strong statistical background to rigorously test prediction accuracy for their specific modeling tasks.
To improve the scientific quality for Rosetta-based modeling we would like to hold a hands-on 2-day workshop aimed at teaching researchers in the Rosetta community practical best-practices for how to analyze their data using rigorous Bayesian statistical modeling.

###Workshop Schedule Outline
The first day we will teach the basics of "tidy data" analysis in R and a principled Bayesian modeling workflow using [Stan](https://mc-stan.org/) and [brms](https://paul-buerkner.github.io/brms/). On the second day we will guide participants to work together to apply the statistical modeling methods to their own data analysis problems.

Day 1 Morning: tidy data analysis in R
* Preparing RStudio environment, and loading and installing packages, RMarkdown
* tidyverse tools: pipe-operator, data I/O, manipulating tables
* Grammar of graphics plotting with ggplot2

Day 1 Afternoon: Bayesian model workflow
* Bayesian theory: Priors + Data => Posterior
* brms/Stan Bayesian regression modeling
* Model evaluation using simulation based calibration
* Model interpretation and hypothesis testing
* BayesPharma dose-response modeling case-study

Day 2:  Bring Your Own Data for hands-on analysis
* Work together in pairs (one partner in the morning, the other in the afternoon)

###Prerequisites
* Basic familiarity with R packages, functions, and data structures
* Concrete regression data analysis task. Attendee must submit data and a modeling question

###Software
* [RStudio](https://www.rstudio.com/products/rstudio/)
* [RStan](https://github.com/stan-dev/rstan/wiki/RStan-Getting-Started)
* C++ Toolchain for [Windows](https://github.com/stan-dev/rstan/wiki/Configuring-C---Toolchain-for-Windows), [Mac](https://github.com/stan-dev/rstan/wiki/Configuring-C---Toolchain-for-Mac), and [Linux](https://github.com/stan-dev/rstan/wiki/Configuring-C-Toolchain-for-Linux)
