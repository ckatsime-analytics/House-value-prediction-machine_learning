## House vrice prediction using machine learning

## Project Overview

This project uses the California Housing dataset to predict median house values based on various socio-economic and geographical features. The goal is to build and compare multiple machine learning models to identify the most accurate approach for housing price prediction.

## Objectives
Analyze housing data and identify key factors affecting prices
Build and evaluate multiple regression models
Improve model performance using advanced techniques like XGBoost
Apply early stopping to prevent overfitting
Select the best-performing model for prediction

## Dataset
Source: Scikit-learn California Housing Dataset
Features include:
Median Income (MedInc)
House Age
Average Rooms
Average Bedrooms
Population
Average Occupancy
Latitude & Longitude

## Models Used
Linear Regression (Baseline Model)
Ridge Regression (Regularization)
XGBoost Regressor (Advanced Model)

## Key Techniques
Train-test split for model validation
Feature scaling using StandardScaler
Model evaluation using R² Score and Mean Squared Error (MSE)
Early Stopping in XGBoost to prevent overfitting
Feature importance analysis

## Results & Findings
Linear Regression showed limited performance due to inability to capture non-linear relationships
Ridge Regression slightly improved stability but still underperformed
XGBoost significantly outperformed other models
Early stopping helped optimize model training and improved generalization

## Model Insight
The results indicate that housing price prediction is a non-linear problem, where advanced ensemble models like XGBoost perform better than traditional linear models.

## Final Model Selection
XGBoost with early stopping was selected as the best model due to:

Higher R² score
Lower prediction error (MSE)
Better generalization to unseen data

## Business Application

#### This model can help:

Real estate companies estimate property values
Buyers and sellers make informed decisions
Analysts understand key drivers of housing prices

## Limitations
Limited feature engineering
Dataset does not include real-time market conditions
XGBoost model is less interpretable compared to linear models
