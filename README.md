# Multiple Linear Regression for House Price Prediction

I worked on this project as part of AISG Foundations In AI Certification.

This project demonstrates the use of Multiple Linear Regression to predict house prices based on various features such as area, number of rooms, and house style.

## Project Overview
The goal of this project is to build a machine learning model that can predict the price of a house based on a set of input features using multiple linear regression.

## Key Features

### 1. Data Preprocessing: 
Includes feature engineering (e.g., calculating the age of a house) and scaling of numerical features.

### 2. Modeling: 
A multiple linear regression model is used to predict the target variable SalePrice.

### 3. Evaluation: 
The model’s performance is evaluated using metrics such as RMSE (Root Mean Squared Error) and R² Score.

### 4. Pipeline: 
The model and preprocessing steps are combined into a single pipeline for efficient execution.


## Requirements
1. Python
2. scikit-learn
3. pandas
4. numpy
5. joblib 

## Dataset Used
The dataset used for this project is the Ames Housing Dataset from Kaggle, which contains data on housing prices and various features of the houses.
Link: https://www.kaggle.com/c/home-data-for-ml-course/data 

## Steps
1. Load Data: The dataset is loaded into a Pandas DataFrame.

2. Data Preprocessing:
- Handle missing values.
- Convert categorical data using OneHotEncoder.
- Standardize numerical features using StandardScaler.

3. Feature Engineering: Calculate the age of the house from the YearBuilt feature.

4. Model Training: Use Multiple Linear Regression to train the model.

5. Model Evaluation: Evaluate model performance using RMSE and R² Score.

6. Save Model: The trained model is saved using joblib for future use.


