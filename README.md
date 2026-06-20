# Customer Churn Prediction Using Machine Learning

## Project Overview

Customer churn is one of the most critical challenges faced by subscription-based businesses. This project aims to predict whether a customer is likely to discontinue services using machine learning techniques.

The solution helps businesses identify at-risk customers and take proactive retention measures.

---

## Business Problem

Acquiring new customers is significantly more expensive than retaining existing ones.

By identifying customers likely to churn, organizations can:

* Improve customer retention
* Reduce revenue loss
* Develop targeted marketing campaigns
* Improve customer satisfaction

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Dataset

IBM Telco Customer Churn Dataset

Dataset includes:

* Customer demographics
* Service subscriptions
* Contract details
* Billing information
* Churn status

---

## Project Workflow

### 1. Data Collection

Loaded and explored telecom customer data.

### 2. Data Cleaning

* Handled missing values
* Converted TotalCharges to numeric format
* Removed unnecessary columns

### 3. Exploratory Data Analysis

Performed analysis to identify patterns associated with customer churn.

### 4. Feature Engineering

* Encoded categorical variables
* Prepared data for machine learning algorithms

### 5. Model Development

Trained and evaluated:

* Logistic Regression
* Decision Tree
* Random Forest

### 6. Model Evaluation

Evaluated models using:

* Accuracy Score
* Confusion Matrix
* Classification Report

### 7. Feature Importance

Identified key factors influencing customer churn.

## Visualizations

### Churn Distribution

<img src="images/churn_distribution.png" width="700">

### Contract Type vs Churn

<img src="images/contract_vs_churn.png" width="700">

### Feature Importance

<img src="images/feature_importance.png" width="700">

---

## Key Findings

* Customers with month-to-month contracts are more likely to churn.
* Customers with shorter tenure have higher churn rates.
* Higher monthly charges increase churn probability.
* Long-term contract customers are less likely to leave.

---

## Business Recommendations

* Introduce loyalty rewards for new customers.
* Encourage customers to switch to long-term contracts.
* Design targeted retention campaigns for high-risk customer segments.
* Provide personalized offers for customers with high monthly charges.

---

## Project Outcome

Successfully developed a machine learning model capable of predicting customer churn and generating actionable business insights to support customer retention strategies.
