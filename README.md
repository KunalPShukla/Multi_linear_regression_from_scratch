# Multi_linear_regression_from_scratch

## Overview
This project implements **Multi-Linear Regression from scratch** using **NumPy**. The model is trained using the **California Housing dataset**, applying **gradient descent** for optimization. Feature scaling is done using **StandardScaler** from `sklearn.preprocessing`. The primary focus is on building the regression model, so **exploratory data analysis (EDA) is not included**.

## Features
- Implements **Multi-Linear Regression** without using built-in libraries.
- Uses **gradient descent** for optimization.
- Applies **feature scaling** with `StandardScaler`.
- Evaluates the model using **R² score**.

## Dataset
The model uses the **California Housing dataset**, which is fetched via `sklearn.datasets.fetch_california_housing()`. The dataset contains features such as:
- Median Income
- House Age
- Average Rooms
- Population, etc.

## Model Implementation
The `Multi_Linear_Regression` class includes:
- **`fit(X_train, y_train)`** – Trains the model using gradient descent.
- **`predict(X_test)`** – Makes predictions on new data.
- **`evaluate(X_test, y_test)`** – Computes and prints the R² score.

## Evaluation
After training, the model is evaluated using the **R² score**, which measures how well the model fits the data.
