# Bulldozer-Price-Prediction
This project aims to predict the future sale price of bulldozers based on their characteristics and historical sales data. The analysis follows an end-to-end machine learning workflow, from data preprocessing to model evaluation.

## Project Overview
Objective: Accurately predict bulldozer auction prices to support better buying and selling decisions.
Dataset: Sourced from the Kaggle Bluebook for Bulldozers competition, which includes:
- Train.csv: Historical training data up to 2011.
- Valid.csv: Validation data from January 2012 to April 2012.
- Test.csv: Test data from May 2012 to November 2012.

## Method
1. Exploratory Data Analysis (EDA): Assessed missing data, outliers, and data distribution. Parsed and enriched date features to leverage time-based patterns. Visualized relationships between key features and sale prices.
2. Data Preprocessing: Cleaned and sorted time-series data. Feature engineering using date components.
3. Model Building: Implemented a baseline using the RandomForestRegressor. Optimized using hyperparameter tuning to minimize prediction error.
4. Evaluation: Used the Root Mean Squared Log Error (RMSLE) as the primary evaluation metric. Assessed model performance using cross-validation.

## Tools
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- RandomForestRegressor

## Outcome
The project successfully demonstrates an end-to-end workflow for predicting bulldozer prices using machine learning, with a focus on practical steps like handling time-series data, hyperparameter tuning, and model validation.
