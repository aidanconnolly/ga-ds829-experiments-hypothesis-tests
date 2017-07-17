# More-Statistics-and-Visualizations
Unit 2 : Working with Data | Lesson 2 : More Statistics and Visualizations

**Notebook:** [More-Statistics-and-Visualizations.ipynb](./More-Statistics-and-Visualizations.ipynb)
**Solutions:** [More-Statistics-and-Visualizations-solutions.ipynb](./solutions-code/More-Statistics-and-Visualizations-solutions.ipynb)

**Extra:** [French Fries & Diabetes Study](./assets/french-fry.pdf) Includes a sample study that shows a use of some of the hypothesis testing, confidence interval, and causation topics. This study is optional and not referenced in any other documents.



### Learning Objectives
- **Explain** the difference between causation and correlation
- **Determine** causality and sampling bias using Directed Acyclic Graphs
- **Identify** what missing data is and how to handle it
- **Test** a hypothesis using a sample case study


### Lesson Guide
- [Data Source](#data-source)
	- [What are the features/covariates/predictors?](#what-are-the-featurescovariatespredictors)
	- [What is the outcome/response?](#what-is-the-outcomeresponse)
	- [What do you think each row in the dataset represents?](#what-do-you-think-each-row-in-the-dataset-represents)
- [Math review](#math-review)
	- [Covariance](#covariance)
	- [Correlation](#correlation)
	- [The variance-covariance matrix](#the-variance-covariance-matrix)
- [Causation and Correlation](#causation-and-correlation)
	- [Structure of causal claims](#structure-of-causal-claims)
	- [Why do we care?](#why-do-we-care)
	- [How do we determine if something is causal?](#how-do-we-determine-if-something-is-causal)
- [Pearlean Causal DAG model](#pearlean-causal-dag-model)
	- [What is a DAG?](#what-is-a-dag)
	- [It's possible that X causes Y.](#its-possible-that-x-causes-y)
	- [Y causes X.](#y-causes-x)
	- [The correlation between X and Y is not statistically significant.](#the-correlation-between-x-and-y-is-not-statistically-significant)
	- [X or Y may cause one or the other indirectly through another variable.](#x-or-y-may-cause-one-or-the-other-indirectly-through-another-variable)
	- [There is a third common factor that causes both X and Y.](#there-is-a-third-common-factor-that-causes-both-x-and-y)
	- [Both X and Y cause a third variable and the dataset does not represent that third variable evenly.](#both-x-and-y-cause-a-third-variable-and-the-dataset-does-not-represent-that-third-variable-evenly)
	- [Controlled Experiments](#controlled-experiments)
	- [When is it OK to rely on association?](#when-is-it-ok-to-rely-on-association)
	- [How does association relate to causation?](#how-does-association-relate-to-causation)
- [Sampling bias](#sampling-bias)
	- [Forms of sampling bias](#forms-of-sampling-bias)
	- [Problems from sampling bias](#problems-from-sampling-bias)
	- [Recovering from sampling bias](#recovering-from-sampling-bias)
    - [Stratified random sampling](#stratified-random-sampling)
- [Missing data](#missing-data)
	- [Types of missing data](#types-of-missing-data)
	- [De minimis](#de-minimis)
	- [Class imbalance](#class-imbalance)
    - [Relation to machine learning](#relation-to-machine-learning)
- [Introduction to Hypothesis Testing](#introduction-to-hypothesis-testing)
	- [Validate your findings](#validate-your-findings)
	- [Confidence intervals](#confidence-intervals)
	- [Error types](#error-types)
- [Scenario](#scenario)
	- [Exercises](#exercises)
	- [Statistical Tests](#statistical-tests)
	- [Interpret your results](#interpret-your-results)
