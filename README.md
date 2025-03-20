# Predicting White Abalone Rings

## Introduction
The white Abalone (Haliotis sorenseni), is an endangered marine mollusk found along the Pacific coast of North America. The purpose of this experiment is to train multiple Machine Learning algorithms to predict ring count via three predictors: length, diameter, and height. Random Forest Regressor, Linear Regression, and XGBoost models will be used for training.

## What is the Target/***Dependent*** Variable?
rings: The age of abalone is determined by cutting the shell through the cone, staining it, and counting the number of rings through a microscope.

## What Feature/***Independent*** Variables are there?
| Feature              | Description                                                                                     |
|----------------------|-------------------------------------------------------------------------------------------------|
| sex            | (M)ale, (F)emale, and (I)nfant.                        |
| length             | Longest shell measurement.                      |
| diameter     | Perpendicular to length.                |
| height           | With meat in shell.                                                          |
| whole_weight        | Grams whole abalone.                                                       |
| shucked_weight           | Grams weight of meat.                                               |
| viscera_weight           | Grams gut weight, after bleeding. |
| shell_weight         | Grams after being dried. |
| rings       | "rings"+ (1.5) equals age in years.                                              |

## What dependencies are required?
| Package      | Description                                                                                   |
|--------------|-----------------------------------------------------------------------------------------------|
| pandas       | A library for data manipulation and analysis, providing data structures like DataFrames.      |
| matplotlib   | A plotting library for creating static, animated, and interactive visualizations in Python.  |
| seaborn      | A statistical data visualization library based on matplotlib, providing a high-level interface.|
| scikit-learn | A machine learning library for Python, offering simple and efficient tools for data mining and analysis. |
| numpy        | A library for numerical computations in Python, providing support for large, multi-dimensional arrays and matrices. |
| xgboost      | An optimized gradient boosting library designed to be highly efficient, flexible, and portable. |
| optuna       | An optimization framework designed to automate the process of finding the best hyperparameters for machine learning models.|
