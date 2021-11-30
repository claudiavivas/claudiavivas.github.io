---
layout: archive
title: ""
permalink: /codes/
author_profile: true
---

# Machine Learning and Causal Inference 

Here are Jupyter Notebooks scripts, my fellows Eljaer Eusebio, Andre Tapia, Luis Sandoval and I replicated for our course of Machine Learning and Causal Inference.

## Replication of "Estimating Treatment Effects with Causal Forests: An Application" - Athey S. & Wagner S. 

Here I replicate the results of the article ‘Estimating Treatment Effects with Causal Forests: An Application’ by Athey and Wager.

Script available for R [here](https://github.com/claudiavivas/Machine-Learning-and-Causal-Inference/blob/main/Lab6/Lab6_R.ipynb)

## Causal Trees 

We used an abridged version of a public dataset from the General Social Survey (GSS) (Smith, 2016). The setting is a randomized control trial. Individuals were asked about their thoughts on government spending on the social safety net. The treatment is the wording of the question: about half of the individuals were asked if they thought government spends too much on "welfare" $(W_i = 1)$, while the remaining half was asked about "assistance to the poor" $(W_i = 0)$. The outcome is binary, with $Y_i = 1$ corresponding to a positive answer. We applicated honest causal tree estimation using the Pennsylvania re-employment bonus experiment data.

Script available for R [here](https://github.com/claudiavivas/Machine-Learning-and-Causal-Inference/blob/main/Lab5/Causal_trees.Rmd)

## Bootstrapping using unemployment databases

The bootstrap can be used to estimate the standard errors of the coefficients from a linear regression fit, or a confidence interval for that coefficient. The power of the bootstrap lies in the fact that it can be easily applied to a wide range of statistical learning methods. In this replication, we use the Pennsylvania re-employment bonus experiment in order to compare treatment group 4 and the control group, for this purpose, we compute the standard errors of 1,000 bootstrap estimates for the $T4$, $female$ and $black$ variables.

Script available for R and Python [here](https://github.com/claudiavivas/Machine-Learning-and-Causal-Inference/tree/main/Lab5)

## Double Lasso - Testing the Convergence Hypothesis

Double-Lasso models, its method combines a regression model with a process of contractions of some parameters to zero and imposes a restriction or penalty on the regression coefficients, to select variables by two step, finding those that predict the dependent variable and those relative to independent variable. We work with countries characteristics database in order to test the convergence hypothesis (Barro-Lee growth data) using Double Lasso approach. 

Script available for R and Python [here](https://github.com/claudiavivas/Machine-Learning-and-Causal-Inference/tree/main/Lab4)

## Analyzing RCT data with Precision Adjustment

We analyze the Pennsylvania reemployment bonus experiment that were conducted to test the incentive effects of alternative compensation schemes for unemployment insurance, here we focus on treatment group 2. Under RCT, the projection coefficient $\beta_1$ has the interpretation of the causal effect of the treatment on the average outcome. We thus refer to $\beta_1$ as the average treatment effect (ATE). For estimation we consider three approaches: classical 2-sample approach, no adjustment (CL), classical linear regression adjustment (CRA) and interactive regression adjusment (IRA). 

Script available for R and Python [here](https://github.com/claudiavivas/Machine-Learning-and-Causal-Inference/tree/main/Lab3)

## The Gender Wage Gap using Mincer equation
Analysis of the difference in the payment of men and women (gender wage gap) usig the Mincer equation. OLS and OLS with controlled features are used for the estimation.

Script available for R and Python [here](https://github.com/claudiavivas/Machine-Learning-and-Causal-Inference/tree/main/Lab1)

## Debiased Machine Learning

Script available for R and Python [here](https://github.com/claudiavivas/Machine-Learning-and-Causal-Inference/blob/main/Lab6/Lab6_R.ipynb)

## The Gender Wage Gap using Mincer equation
Analysis of the difference in the payment of men and women (gender wage gap) usig the Mincer equation. Lasso approach is used for the estimation.

Script available for R and Python [here](https://github.com/claudiavivas/Machine-Learning-and-Causal-Inference/tree/main/Lab2)

# Activities in Economics 2
My fellows, Luis Meza and Angiluz Remigio, and I replicated the paper "Desigualdad en los ingresos Género y lengua materna - Garavito Cecilia" for our Stata course. [Here](https://github.com/claudiavivas/Activities-in-economy-2) is the GitHub repository with the replication codes.