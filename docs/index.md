---
layout: default
title: Home
header: Machine Learning from Time Series
nav_order: 1
---

Time series classification and regression are rapidly evolving fields that find areas of application in all domains of machine learning and data science. This hands on tutorial will provide an accessible overview of the recent research in these fields, using code examples to introduce the process of implementing, building and evaluating an estimator for time series data. We will show how to easily reproduce published results and how to compare a new algorithm to the state-of-the-art. Finally, we will work through real world examples from the field of Electroencephalogram (EEG) classification and regression. EEG machine learning tasks arise in medicine, brain-computer interface research and psychology. We use these problems to how to compare algorithms on problems from a single domain and how to deal with data with different characteristics, such as missing values, unequal length and high dimensionality. The latest advances in the fields of time series classification  \[[2](https://doi.org/10.1007/s10618-016-0483-9),[3](https://doi.org/10.1007/s10618-024-01022-1)\] and regression  \[[4](https://doi.org/10.1007/s10618-021-00745-9),[5](https://doi.org/10.1007/s10618-024-01027-w)\] are all available through the _aeon_ toolkit \[[1](https://doi.org/10.48550/arXiv.2406.14231)\], an open source, _scikit-learn_ compatible framework for time series machine learning which we use to provide our code examples.

The talk will be a mix of lecture style and code examples. There will be a Jupyter notebook available for each topic, while it is not likely all the content in these will be covered in the talk itself we invite viewers to run through them ask any questions they have.

## When & Where

- **Conference:** [KDD 2024](https://www.kdd.org/kdd2024/)
- **Date:** Monday, August 26
- **Time:** 14:00 (EEST)
- **Room:** 124-125

## Target Audience

This tutorial is aimed at those interested in time series machine learning research, with a focus on classification and regression with ordered data. We use EEG problems to demonstrate all key time series classification and regression methods, but we aim to appeal to any data scientist whose area of application may give rise to such data.

## Prerequisites

- Basic machine learning background
- Basic understanding of programming in Python and/or Jupyter notebooks
- Not required but helpful: Basic understanding of the _scikit-learn_ Python package

## References

[[1]](https://doi.org/10.48550/arXiv.2406.14231)  __Matthew Middlehurst__, __Ali Ismail-Fawaz__, __Antoine Guillaume__, Christopher Holder, __David Guijo Rubio__, Guzal Bulatova, Leonidas Tsaprounis, Lukasz Mentel, Martin Walter, Patrick Schäfer, __Anthony Bagnall__. aeon: a Python toolkit for learning from time series. arXiv preprint arXiv:2406.14231, 2024.

[[2]](https://doi.org/10.1007/s10618-016-0483-9) __Anthony Bagnall__, Jason Lines, Aaron Bostrom, James Large, and Eamonn Keogh. The great time series classification bake off: a review and experimental evaluation of recent algorithmic advances. Data Mining and Knowledge Discovery, 31(3):606–660, 2017.

[[3]](https://doi.org/10.1007/s10618-024-01022-1) __Matthew Middlehurst__, Patrick Schäfer, and __Anthony Bagnall__. Bake off redux: a review and experimental evaluation of recent time series classification algorithms. Data Mining and Knowledge Discovery, 1-74, 2024.

[[4]](https://doi.org/10.1007/s10618-021-00745-9) __Chang Wei Tan__, Christoph Bergmeir, Francois Petitjean, and __Geoffrey Webb__. Time series extrinsic regression. Data Mining and Knowledge Discovery, 35:1032––1060, 2021.

[[5]](https://doi.org/10.1007/s10618-024-01027-w) __David Guijo-Rubio__, __Matthew Middlehurst__, Guilherme Arcencio, Diego Furtado Silva, and __Anthony Bagnall__. Unsupervised feature based algorithms for time series extrinsic regression. Data Mining and Knowledge Discovery, 1-45, 2023.