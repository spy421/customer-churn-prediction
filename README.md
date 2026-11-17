# Customer Churn Prediction

# Project Overview
This project focuses on predicting customer churn for a telecommunications company using Machine Learning.

The goal is to identify customers who are likely to leave the company and provide actionable business recommendations to improve customer retention.

## Business Problem
Customer churn directly affects company revenue. By identifying customers at risk of leaving, the business can take proactive measures to retain them.

## Dataset
- Source: IBM Telco Customer Churn Dataset
- Rows: 7,043
- Features: 19 input features
- Target variable: `Churn`

## Data Cleaning
- Converted `TotalCharges` from string to numeric.
- Handled 11 missing values.
- Checked and confirmed there were no duplicate rows.
- Prepared features and target variable.

## Exploratory Data Analysis
Analyzed customer characteristics and their relationship with churn.

## Machine Learning
- Model: Logistic Regression
- Train/test split: 80/20
- Encoding: One-Hot Encoding
- Class imbalance handling: `class_weight="balanced"`

## Model Evaluation
The model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

A classification threshold of 0.3 achieved a churn recall of approximately 0.86 in the experiment.

This means the model identified approximately 86% of actual churn customers in the test set.

## Business Recommendations
Based on the model results:
1. Focus retention campaigns on customers with high churn probability.
2. Improve customer support for fiber-optic internet users.
3. Offer targeted discounts to month-to-month customers.
4. Monitor customer satisfaction and service quality.

## Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Author
Machine Learning / Data Analytics Portfolio Project
