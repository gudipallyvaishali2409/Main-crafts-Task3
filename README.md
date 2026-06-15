# House Price Prediction - AIML Task 3

## Project Overview

This project demonstrates a complete Machine Learning workflow for house price prediction using regression algorithms. The objective is to build predictive models, evaluate their performance, detect overfitting, perform hyperparameter tuning, and scientifically justify the final model selection.

## Objectives

* Detect and control overfitting
* Validate models using Cross Validation
* Tune model hyperparameters systematically
* Improve model generalization performance

## Dataset

The project uses the California Housing Dataset available in Scikit-Learn.


Target Variable:

* Median House Value

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-Learn
* Matplotlib
* Seaborn
* Pickle

## Machine Learning Workflow

### 1. Data Loading

The California Housing dataset is loaded using Scikit-Learn.

### 2. Data Preprocessing

* Feature selection
* Train-test splitting
* Feature scaling using StandardScaler

### 3. Model Development

The following regression models are implemented:

* Linear Regression
* Ridge Regression
* Decision Tree Regressor


### 4. Model Evaluation

Models are evaluated using:

* R² Score
* RMSE (Root Mean Squared Error)

### 5. Overfitting Detection

Training and testing scores are compared to identify overfitting.

Example:

Train R² = 1.00

Test R² = 0.62

This indicates severe overfitting.

### 6. Cross Validation

5-Fold Cross Validation is performed to obtain reliable performance estimates.

### 7. Hyperparameter Tuning

GridSearchCV is used to optimize:

* max_depth
* min_samples_split

for the Decision Tree Regressor.

### 8. Model Comparison

All models are compared using training and testing metrics.

### 9. Final Model Selection

The final model is selected based on:

* Test Performance
* Cross Validation Score
* Generalization Ability
* Reduced Overfitting

## Results

The project demonstrates how model complexity affects performance and how hyperparameter tuning can reduce overfitting while improving generalization.



