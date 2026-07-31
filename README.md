# 📉 Telco Customer Churn Prediction

A machine learning project that predicts customer churn for a telecom company using classification models, helping identify at-risk customers before they leave.

## 📊 Overview

Customer churn is a critical metric for telecom companies, where retaining existing customers is significantly cheaper than acquiring new ones. This project analyzes customer usage, billing, and demographic data to predict which customers are likely to discontinue their service, enabling proactive retention strategies.

## 🔧 Tech Stack

- **Python** – Core programming language
- **Pandas, NumPy** – Data manipulation and preprocessing
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – Model building and evaluation
- **Jupyter Notebook** – Development environment

## ✨ Features

- **Exploratory Data Analysis (EDA)** – Identified key patterns and correlations between customer attributes and churn behavior
- **Feature Engineering** – Encoded categorical variables and created derived features to improve model performance
- **Model Building** – Trained and compared multiple classification algorithms:
  - Logistic Regression
  - Random Forest
  - XGBoost
- **Model Evaluation** – Assessed models using accuracy, precision, recall, F1-score, and confusion matrix
- **Data Visualization** – Visualized churn trends across contract type, tenure, monthly charges, and payment method

## 🗂️ Dataset

The dataset includes customer-level information such as:

| Feature | Description |
|---|---|
| `tenure` | Number of months the customer has stayed |
| `Contract` | Contract type (Month-to-month, One year, Two year) |
| `MonthlyCharges` | Monthly bill amount |
| `TotalCharges` | Total amount charged |
| `PaymentMethod` | Mode of payment |
| `InternetService` | Type of internet service |
| `Churn` | Target variable (Yes/No) |



**Author:** Sumit Raj  
🔗 [LinkedIn](https://www.linkedin.com/in/sumitr15/)
