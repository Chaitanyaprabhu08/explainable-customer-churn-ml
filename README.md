# Explainable Customer Churn Prediction

A machine learning project for predicting telecom customer churn and understanding the factors behind customer churn.

The project uses machine learning models, SHAP explainability, and K-Means clustering to analyze customer behavior and identify customer groups that may need different retention strategies.

---

## Project Overview

Customer churn is an important problem for telecom companies. Identifying customers who are likely to leave can help companies take action before they churn.

In this project, I:

- analyzed the telecom customer dataset
- cleaned and prepared the data for machine learning
- performed exploratory data analysis
- compared different classification models
- used SMOTE to handle class imbalance
- selected a churn-focused model
- used SHAP to explain model predictions
- used K-Means to segment customers
- developed retention recommendations for different customer segments

---

## Objectives

- Predict whether a customer is likely to churn
- Identify important factors related to churn
- Compare different machine learning models
- Handle class imbalance using SMOTE
- Improve the detection of potential churners
- Explain model predictions using SHAP
- Segment customers using K-Means clustering
- Generate business recommendations based on customer segments

---

## Dataset

The project uses the Telco Customer Churn dataset.

The dataset contains information about:

- Customer demographics
- Partner and dependent status
- Tenure
- Phone and internet services
- Online security and support services
- Contract type
- Payment method
- Monthly charges
- Total charges
- Churn status

### Dataset Information

- Customers: 7,043
- Original columns: 21
- Target variable: `Churn`

The `customerID` column was removed during preprocessing because it is only an identifier and does not provide useful information for prediction.

---

## Project Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Train-Test Split
   ↓
Feature Preprocessing
   ↓
Model Training
   ↓
SMOTE
   ↓
Model Evaluation
   ↓
SHAP Explainability
   ↓
K-Means Customer Segmentation
   ↓
Business Recommendations