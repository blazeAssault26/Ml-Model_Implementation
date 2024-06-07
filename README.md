# ML-from-Scratch

This repository explores fundamental machine learning algorithms implemented from scratch, delving into the underlying mathematics. It uses visualizations to illustrate the internals of each algorithm, enhancing comprehension of their principles and mechanisms.

## Overview

**_Boosting_** is an ensemble learning technique aimed at improving model performance by iteratively combining weak learners, such as decision trees. Unlike traditional ensemble methods like bagging, boosting corrects errors made by previous models sequentially. This adaptive approach enables boosting to capture complex data relationships and achieve high predictive accuracy. This notebook demonstrates Gradient Boosting Machines (GBM), which improve predictions by fitting decision trees to the residuals of previous models. This iterative process refines predictions and minimizes errors. By adapting to data nuances through residual analysis, GBM enhances predictive power beyond individual weak learners. GBM employs additive modeling, where each new tree is added to the model to correct the errors of the previous trees, iteratively reducing the residuals and minimizing the error to zero over subsequent models.

**_Linear regression_** is a foundational statistical technique used to model the relationship between a dependent variable and one or more independent variables by fitting a linear equation to observed data. The objective is to find the best-fitting line that minimizes the sum of squared residuals between observed and predicted values. Mathematically, it involves estimating the coefficients ((β)) in the equation (𝑦 = 𝛽₀ + 𝛽₁𝑥₁ + ⋯ + 𝛽ₙ𝑥ₙ + ϵ) using the Ordinary Least Squares (OLS) method. This method minimizes the sum of the squared differences between observed and predicted values, achieved by solving the normal equation (𝛽 = (𝑋ᵀ𝑋)⁻¹𝑋ᵀ𝑦) where 
X is the matrix of input features and 𝑦 is the vector of output values.This project demonstrates linear regression by implementing it from scratch and comparing it with the scikit-learn library. The custom implementation calculates the slope and intercept manually showcasing the underlying maths, while scikit-learn uses the efficient OLS method internally.
