---
title: Inductive Venn-Abers predictive distribution
abstract: Venn predictors are a distribution-free probabilistic prediction framework
  that transforms the output of a scoring classifier into a (multi-)probabilistic
  prediction that has calibration guarantees, with the only requirement of an i.i.d.
  assumption for calibration and test data. In this paper, we extend the framework
  from classification (where probabilities are predicted for a discrete number of
  labels) to regression (where labels form a continuum). We show how Venn Predictors
  can be applied on top of any regression method to obtain calibrated predictive distributions,
  without requiring assumptions beyond i.i.d. of calibration and test sets. This is
  contrasted with methods such as Bayesian Linear Regression, for which the calibration
  guarantee instead relies on specific probabilistic assumptions on the distribution
  of the data. The adaptation of Venn Machine to regression required a theoretical
  analysis of the transductive and inductive forms of the predictor. We identify potential
  consistency problems and provide solutions for them. Finally, to illustrate their
  advantages, we apply regression Venn Predictors to the medical problem of predicting
  the survival time after Percutaneous Coronary Intervention, a potentially risky
  procedure that improves blood flow to a patient’s heart. The predictive distributions
  obtained with this method allow a variety of interpretations that include probability
  of survival time exceeding a chosen threshold or the shortest survival time guaranteed
  with a given probability.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: nouretdinov18a
month: 0
tex_title: Inductive {V}enn-{A}bers predictive distribution
firstpage: 15
lastpage: 36
page: 15-36
order: 15
cycles: false
author:
- given: Ilia
  family: Nouretdinov
- given: Denis
  family: Volkhonskiy
- given: Pitt
  family: Lim
- given: Paolo
  family: Toccaceli
- given: Alexander
  family: Gammerman
date: 2018-06-07
address: 
publisher: PMLR
container-title: Proceedings of the Seventh Workshop on Conformal and Probabilistic
  Prediction and Applications
volume: '91'
genre: inproceedings
issued:
  date-parts:
  - 2018
  - 6
  - 7
pdf: http://proceedings.mlr.press/v91/nouretdinov18a/nouretdinov18a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
