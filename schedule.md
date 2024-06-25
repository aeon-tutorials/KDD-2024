---
layout: default
title: Schedule
nav_order: 2
---

- Introduction to Time Series Machine Learning (TB)

    todo

- Distance Measure for Time Series (GW)

    Many classifiers and regressors use a distance or similarity functions between whole time series as the basis for prediction. Historically, distance functions have been mostly used with Nearest Neighbour (NN) classifiers such as 1-NN Dynamic Time Warping (1NN-DTW). Alternative uses of time series distances are described in~\cite{abanda19distance}. We will highlight recent work in comparing time series using distances and give a hands-on demonstration of how we can define a new distance function in _aeon_ to use with _scikit-learn_ or _aeon_ estimators.

- Convolutional Kernels (15 Mins, by GW)

    Kernel/Convolution classifiers use convolutions with kernels, which can be seen as subseries used to derive discriminatory features. Each kernel is convolved with a time series through a sliding dot product creating an activation map. We will review the ROCKET family of algorithms and use these algorithms to demonstrate parameter tuning in _aeon_. 

- Summary Features (15 Mins, by MM)

    A family of popular approaches involve extracting global features passed to a standard estimator in a simple pipeline. We will review popular feature generators such as Catch22 and TSFresh, and demonstrate how to create simple feature estimators using the _aeon_ transformation interface and the pipeline utilities present in both _aeon_ and _scikit-learn_.

- Phase Dependant Intervals: (15 Mins, by MM)

    Features found from the whole series may be confounded by noise. Another family of algorithms mitigate against this by finding intervals from numerous extracted subseries called intervals. In addition to demonstrating usage and providing examples of when interval methods may be useful we will demonstrate some of the visualisation techniques available for evaluating feature importance.

- Dictionary-based Bag-of-word Models (15 Mins, by AF)

    Dictionary based approaches use histograms of counts of repeating patterns as features for the estimator. We will describe these estimators and use them to highlight different design patterns used in TSC and TSER research in terms of ensembles vs pipelines and randomisation vs optimisation.  

- Deep Learning for Time Series (15 Mins, by GF)

    Since a review of deep learning classification in 2019 numerous algorithms have been proposed, such as InceptionTime and its variants. We will provide a short summary of work in this area before reviewing the basic structure of deep learners and show how to structure a new deep learning estimator. 

- Phase Independant Shapelets (15 Mins, by TB)

    Shapelets are phase independent discriminatory subseries taken from the training data. They have proved a popular primitive for classification. One feature of shapelets is the ability to trace important shapelets back to the training data to give domain specific insights. We will demonstrate how to simply do this in _aeon_.

- Hybrid Approaches (15 Mins, by TB)

    This type of method combines two or more of the above approaches. The nature of the data and the problem dictate which category of algorithm is most appropriate. The most accurate algorithms on average, with no a-priori knowledge of the best approach, combine multiple transformation types in a hybrid algorithm. We define a hybrid algorithm as one which by design encompasses or ensembles multiple of the discriminatory representations we have previously described. One family of hybrid estimators are meta-ensembles. We will demonstrate how to build a bespoke hybrid ensemble classifier using the estimators covered in the tutorial.

- A Case Study of Electroencephalography (EEG) Data - (15 Mins, by TB)

    Classification and regression problems commonly arise EEG research: in medicine there are applications in early disease diagnosis and, for example, understanding fibromyalgia. In psychology EEG are used to study the brain processes underlying attention, learning, and memory. In BCI the task is to link patterns of EEG to physical or virtual actions. Each field has an extensive literature and preferences for algorithms. We use examples of EEG classification and regression to demonstrate standard workflows using _aeon_, to explore algorithm capabilities for high dimensional, unequal length data with potential missing values and to assess the scalability of selected algorithms.

- Conclusion and Future Outlook (15 Mins, by TB)

    todo
