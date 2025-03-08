Car Price Prediction Model
This repository contains a machine learning project that predicts the prices of cars based on various features such as brand, model, engine specifications, body type, mileage, and more. The goal is to train several regression models and evaluate their performance on a real-world dataset of used cars.

Project Overview
Objective: Predict the price of used cars based on various features.
Dataset: The dataset consists of 17,145 entries with 17 features, including both numerical and categorical data. Key features include car brand, model, year of manufacture, body type, mileage, condition, and more.
Models Evaluated:
XGBoost Regressor
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regression (SVR)
Linear Regression

Steps
Data Preprocessing:
Missing values handled.
Categorical variables were encoded.
Numerical features were scaled.
Exploratory Data Analysis (EDA):
Performed an in-depth analysis of the dataset to identify correlations and potential data relationships.
Visualizations were used to better understand how different features impact car prices.

Model Training:
Multiple regression models were trained and evaluated based on Mean Squared Error (MSE) and R² score metrics.
Random Forest Regressor was found to be the best performing model.

Best Model
Random Forest Regressor was the most accurate model, producing the lowest MSE and highest R² scores for both training and testing datasets. The model was capable of capturing non-linear relationships and interactions between features effectively.