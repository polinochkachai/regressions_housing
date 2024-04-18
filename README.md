# House Price Prediction

## Overview

The house price prediction system aims to provide accurate estimates of house prices using regression models. It leverages machine learning techniques to analyze housing data and make predictions based on key features.

## Methods 

### Linear Regression
Assumes a linear relationship between predictor variables and the target variable. It finds the best-fitting line (or hyperplane) that minimizes the sum of squared differences between actual and predicted values.

### Ridge Regression
Adds a penalty term (L2 regularization) to the linear regression objective function to mitigate multicollinearity. It shrinks the coefficients towards zero to improve model stability.

### Lasso Regression
Adds a penalty term (L1 regularization) to the linear regression objective function. It performs feature selection by driving some coefficients to exactly zero, effectively removing irrelevant features.

### Decision Tree
Builds a tree-like structure where each node represents a decision based on a feature. It recursively splits the data to maximize homogeneity within each subset.

### Random Forest
Constructs a large number of decision trees and aggregates their predictions to reduce overfitting. It introduces randomness during the tree-building process to improve prediction accuracy.

### Gradient Boosting
Combines multiple weak learners (decision trees) to create a strong learner. It builds trees sequentially, with each new tree correcting the errors made by the previous ones.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
