Comparing Regression Models for Biomechanics Prediction

This project evaluates and compares different regression algorithms for predicting biomechanical variables based on input sensor data. The goal is to analyze model accuracy to determine the most effective machine learning approach.

The dataset contains 16 input variables recorded from body-worn sensors, along with 4 target variables that represent important biomechanical quantities like joint forces or torque.

A pipeline workflow is implemented that performs standardization of the input data then trains each regression model using 10-fold cross-validation. Multiple models are evaluated including linear regression, LASSO, SVM, decision tree, and neural network regressors.

By training each model in a consistent standardized pipeline with cross-validation, unbiased estimates of generalization performance are obtained. The cross-validation scores for model accuracy (mean squared error) provide insight into how effectively each learning algorithm can predict the target variables from the given input data.

This analysis provides a data-driven approach to select optimal regression models for estimating biomechanical variables from wearable sensors. The results can guide the development of machine learning tools for sports analytics and injury prevention applications.

