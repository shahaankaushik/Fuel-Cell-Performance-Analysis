# Fuel-Cell-Performance-Analysis

Overview

This repository contains Python code to analyze and predict fuel cell performance using multiple regression models. The workflow includes data preprocessing, exploratory data analysis (EDA), training multiple machine learning models, and evaluating their performance.

Features

Data Preprocessing:
Handles missing values.
Encodes categorical features.
Scales numerical features for better model performance.

Exploratory Data Analysis (EDA):
Visualizes the distribution of the target variable.

Model Training:

Trains multiple models including:
Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor

Model Evaluation:
Evaluates models using Mean Squared Error (MSE) and R2 Score.
Compares model performance visually.



Models Used

Linear Regression: A baseline model for regression.

Decision Tree Regressor: A non-linear model for capturing complex patterns.

Random Forest Regressor: An ensemble model combining multiple decision trees.

Gradient Boosting Regressor: A robust model that optimizes performance iteratively.


Results

The script evaluates each model using:

Mean Squared Error (MSE): Measures the average squared difference between actual and predicted values.

R2 Score: Indicates how well the model explains the variance in the target variable.

Results are saved in model_results_target5.csv and visualized in bar plots.

