---
layout: post
title: Piecewise-Linear Approximations and Filtering for DSGE Models with Occasionally-Binding Constraints
modified:
categories: published
excerpt: Joint with <a href="http://aruoba.econ.umd.edu"> Bora&#x11F;an Aruoba (Maryland)</a>, Kenji Higa-Flores (Maryland), <a href="http://sites.sas.upenn.edu/schorf">Frank Schorfheide (UPenn)</a> and Sergio Villalvazo (UPenn). <br> <i>Review of Economic Dynamics, forthcoming</i>.
tags: []
link:
image:
  feature: sample-image-line.jpg
date: 2021-01-27T00:18:40-04:00
---
#### With [Bora&#x11F;an Aruoba (Maryland)](http://aruoba.econ.umd.edu/), Kenji Higa-Flores (Maryland), [Frank Schorfheide (UPenn)](http://sites.sas.upenn.edu/schorf) and [Sergio Villalvazo (UPenn)](https://www.sergiovillalvazo.com).

<p style="text-align:justify">
We develop an algorithm to construct approximate decision rules that are piecewise- linear and continuous for DSGE models with an occasionally binding constraint. The functional form of the decision rules allows us to derive a conditionally optimal particle filter (COPF) for the evaluation of the likelihood function that exploits the structure of the solution. We document the accuracy of the likelihood approximation and embed it into a particle Markov chain Monte Carlo algorithm to conduct Bayesian estimation. Compared with a standard bootstrap particle filter, the COPF significantly reduces the persistence of the Markov chain, improves the accuracy of Monte Carlo approximations of posterior moments, and drastically speeds up computations. We use the techniques to estimate a small-scale DSGE model to assess the effects of the government spending portion of the American Recovery and Reinvestment Act in 2009 when interest rates reached the zero lower bound.</p>
{: .text-justify}

Link to [paper](https://doi.org/10.1016/j.red.2020.12.003).
Link to [local copy](/documents/ACS-PLC-v9.pdf).
Replication [code](https://github.com/pcuba/RED-PLC-Estimation)
<br>
{: .notice}
