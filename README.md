# Customer Churn Prediction & Lifetime Value (LTV) Analysis

## Project Overview

This project focuses on analyzing customer churn behavior and predicting customer lifetime value (LTV) for a telecommunications company.

The objective is to understand customer churn patterns, identify important factors affecting customer decisions, and predict future customer revenue using machine learning techniques.

The project includes data preprocessing, exploratory data analysis, churn analysis, machine learning model development, and FastAPI deployment for customer lifetime revenue prediction.

---

# Dataset Information

**Dataset Used:** Telco Customer Churn Dataset

The dataset contains customer information including demographics, subscription details, billing information, services used, and churn status.

## Key Features

- Gender
- SeniorCitizen
- Partner
- Dependents
- Tenure
- InternetService
- Contract
- PaymentMethod
- MonthlyCharges
- TotalCharges
- Churn

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Random Forest Algorithm
- FastAPI
- Uvicorn
- Jupyter Notebook
- GitHub

---

# Project Workflow
Dataset Collection
↓
Data Cleaning
↓
Data Preprocessing
↓
Exploratory Data Analysis (EDA)
↓
Feature Engineering
↓
Customer Churn Analysis
↓
Lifetime Value Prediction Model
↓
FastAPI Deployment


---

# Current Progress

Completed:

- Project setup completed
- Dataset imported
- Data cleaning performed
- Missing values handled
- Data types converted
- Outlier detection completed
- Exploratory Data Analysis performed
- Churn distribution analysis completed
- Feature importance analysis completed
- Machine learning model developed
- Customer Lifetime Value prediction completed
- FastAPI prediction service created

---

# Customer Churn Analysis

The project analyzes customer behavior to identify factors responsible for customer churn.

The analysis helps in:

- Understanding customer retention patterns
- Identifying high-risk customers
- Improving customer retention strategies
- Supporting business decision-making

---

# Lifetime Value (LTV) Prediction

A machine learning regression model was developed to predict customer lifetime revenue.

## Model Used

**Random Forest Regressor**

## Why Random Forest?

- Handles complex customer behavior patterns
- Works effectively with multiple features
- Reduces overfitting compared to individual decision trees
- Provides feature importance insights

---

# Model Insights

- Customer characteristics and service usage patterns influence lifetime revenue prediction.
- Feature importance analysis helps identify the factors contributing most to customer value.
- The model can help businesses identify valuable customers.
- Revenue prediction supports better marketing and retention strategies.

---

# FastAPI Deployment

A FastAPI service was created to provide real-time customer revenue predictions.

## Single Customer Prediction

Endpoint:

Purpose:

Predict lifetime revenue for an individual customer.

---

## Batch Prediction

Endpoint:

Purpose:

Predict revenue for multiple customers at the same time.

---

# API Documentation

FastAPI provides interactive API testing using Swagger UI.
http://127.0.0.1:8000/docs

---

# Project Objectives

The main objectives are:

- Predict customer churn
- Identify important churn factors
- Predict customer lifetime value
- Understand customer behavior patterns
- Improve customer retention strategies
- Provide a deployable machine learning prediction service

---

# Future Improvements

- Deploy FastAPI application on cloud platforms
- Create a dashboard for customer analytics
- Improve model performance using advanced algorithms
- Add automated model monitoring
- Build a complete customer management system

---

# Conclusion

This project combines customer churn analysis and lifetime value prediction to provide business insights and predictive solutions.

The final system can analyze customer behavior and predict future revenue using a machine learning model exposed through a FastAPI service.
