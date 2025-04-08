# MachineLearningProblems
This folder contains the codes of machine learning problems I have Implemented during my Lab course at the University. 

1. REGRESSION_CLASSIFICATION_REGULARIZATION.ipynb
   
This file contains problems on:

a. Linear Regression on Time Series Data: Implements linear regression using gradient descent to model time series data.

b. Machine Learning Tools for Regression and Classification: Features a Helper class with utility methods for random sampling, feature normalization, and performance metrics calculation; an Optimization class providing techniques like Stochastic Gradient Descent (SGD) and Newton’s method for parameter optimization; a Loss class defining loss functions such as mean squared error and cross-entropy with regularization options (L1, L2, Elastic Net); and LinearRegression and LogisticRegression classes for model fitting and prediction.

c. Backward Feature Selection: Incorporates feature selection using Akaike Information Criterion (AIC) and Bayesian Information Criterion (BIC) to identify optimal feature subsets.

d. Grid Search with K-Fold Cross-Validation: Performs hyperparameter tuning (learning rate and L2 regularization strength) using grid search combined with k-fold cross-validation.

e. Lasso Regression: Implements a Lasso loss function (l1_regularized_loss) combining residual sum of squares with an L1 penalty, and employs a soft_threshold function for coefficient updates via coordinate descent.
