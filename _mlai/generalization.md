---
layout: lectures
title: "Generalization: Model Validation"
ipynb: True
abstract: "Generalization is the main objective of a machine learning algorithm. The models we design should work on data they have not seen before. Confirming whether a model generalizes well or not is the domain of *model validation*. In this lecture we introduce approaches to model validation such as hold out validation and cross validation."
week: 5
author:
- family: Lawrence
  given: Neil D.
  gscholar: r3SJcvoAAAAJ
  institute: University of Sheffield
  twitter: lawrennd
  url: http://inverseprobability.com
venue: University of Sheffield
youtube: wy0J6cgqlf8
date: 2015-10-27
transition: None
---

\include{talk-macros.tex}

\subsection{Review}

* Last time: introduced basis functions.
* Showed how to maximize the likelihood of a non-linear model that's linear in parameters.
* Explored the different characteristics of different basis function models

\include{_ml/includes/alan-turing-marathon.md}
\include{_ml/includes/expected-loss.md}
\include{_ml/includes/empirical-risk-minimization.md}
\include{_ml/includes/validation.md}
\include{_ml/includes/bias-variance-dilemma.md}

\addreading{@Rogers:book11}{Section 1.5}

\reading

\thanks

\references