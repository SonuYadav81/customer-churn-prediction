# Customer Churn Prediction

A Machine Learning project that predicts whether a customer is likely to churn based on customer demographics, usage, billing and service-related information.

## Project Objective

The objective of this project is to predict customer churn probability using Machine Learning.

## Features

- Synthetic customer dataset generation
- Data cleaning
- Feature engineering
- Numerical and categorical preprocessing
- Logistic Regression
- Churn prediction
- Churn probability
- Model evaluation
- Confusion Matrix
- ROC Curve
- ROC-AUC
- Saved Scikit-learn model

## Dataset

The dataset contains 5,000 customer records.

Features include:

- Customer ID
- Gender
- Age
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Contract
- Payment Method
- Monthly Charges
- Total Charges
- Support Tickets
- Late Payments
- Data Usage
- Number of Services

## Machine Learning Workflow

Customer Data
↓
Data Cleaning
↓
Feature Engineering
↓
Train/Test Split
↓
Preprocessing
↓
Logistic Regression
↓
Churn Prediction
↓
Churn Probability

## Model

The project uses Logistic Regression from Scikit-learn.

The trained model is saved as:

`churn_model.pkl`

## Current Status

Machine Learning and data-processing components are completed.

Backend integration with Python API, Node.js/Express and MongoDB will be added in the next phase.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
