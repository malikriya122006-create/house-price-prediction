# House-Price-Prediction
House price prediction using machine learning models

# Project Overview
this project aims to predict house prices using machine learning techniques.

# Dataset
the dataset contains information about houses such as price , country , bedrooms etc

# Day 1
- loaded dataset
- performed initial data exploration using head(), info(), describe()
- visualised price distribution using histograms
- identified skewness in price
- removed invalid values(price = 0)

# Day 2 
- did EDA, Data Preprocessing & Feature Engineering
- log transformation of price
- handled outliers & skewness in the data
- created new features : price_per_sqft, house_age
- One-hot encoding for city

# Day 3
- did Model Training & Evaluation
- train_test_split
- feature scaling using StandardScaler
- Linear Regression model
- Evaluation:
    r2_score = 0.81
    Calculated MSE,RMSE,MAE 
