# Telecom Customer Churn Analysis & Prediction

# Project Overview
Customer churn is a major challenge for telecom companies as losing customers directly impacts revenue. This project focuses on analyzing customer behavior and predicting churn using machine learning models in Python and visualizing insights through an interactive Power BI dashboard.

The goal is to identify customers who are likely to churn and provide actionable insights that help telecom companies implement effective customer retention strategies.

# Project Architecture

Dataset
   │
   ▼
Data Cleaning & Preprocessing (Python)
   │
   ▼
Exploratory Data Analysis (EDA)
   │
   ▼
Feature Engineering
   │
   ▼
Machine Learning Models
(Logistic Regression, Random Forest, XGBoost)
   │
   ▼
Model Evaluation
   │
   ▼
Business Insights
   │
   ▼
Power BI Dashboard Visualization

# Dataset Overview

The dataset contains telecom customer information such as:

| Feature | Description |
|------|------|
| CustomerID | Unique customer identifier |
| Gender | Customer gender |
| Tenure | Number of months the customer stayed |
| MonthlyCharges | Monthly service charges |
| TotalCharges | Total amount charged |
| Contract | Type of contract |
| InternetService | Internet service type |
| PaymentMethod | Customer payment method |
| Churn | Target variable (Yes/No) |

---

# Step-by-Step Project Workflow

# Data Collection
- The telecom churn dataset was collected and imported into the Python environment for analysis.

# Data Cleaning
Data preprocessing steps included:

- Handling missing values  
- Removing duplicate records  
- Converting incorrect data types  
- Formatting the TotalCharges column to numeric  

---

# Exploratory Data Analysis (EDA)

EDA was conducted to understand customer patterns and churn behavior.

Key analysis performed:

- Churn distribution  
- Contract type vs churn  
- Monthly charges distribution  
- Tenure vs churn relationship  
- Payment method impact on churn  

Visualizations were created using Matplotlib and Seaborn.

---

# Feature Engineering

Categorical variables were transformed into numerical values using:

- Label Encoding  
- One-Hot Encoding  

This step ensures machine learning models can process the data effectively.

---

# Train-Test Split

The dataset was split into:

- 80% Training Data  
- 20% Testing Data  

This helps evaluate model performance on unseen data.

---

# Machine Learning Models

Multiple models were implemented to compare predictive performance.

# Logistic Regression
- Used as a baseline classification model  
- Provides interpretability of feature impact  

# Random Forest
- Ensemble model using multiple decision trees  
- Handles complex feature relationships  

# XGBoost
- Gradient boosting algorithm  
- Provides high prediction accuracy  

---

# Model Evaluation

Models were evaluated using classification metrics.

| Metric | Purpose |
|------|------|
| Accuracy | Overall prediction performance |
| Precision | Correct churn predictions |
| Recall | Ability to detect churn customers |
| F1 Score | Balance between precision and recall |
| Confusion Matrix | Model prediction comparison |

The best-performing model was selected based on these metrics.

---

# Power BI Dashboard Visualization

To support business decision-making, an interactive Power BI dashboard was created to visualize telecom churn insights.

# Dashboard Features

- Total Customers KPI  
- Churn Rate KPI  
- Customer Distribution by Contract Type  
- Churn by Internet Service  
- Monthly Charges Analysis  
- Customer Tenure Analysis  
- Payment Method Distribution  
- Customer Segmentation  

---

# Key Visualizations

The dashboard includes:

- KPI Cards  
- Pie Charts  
- Clustered Bar Charts  
- Line Charts  
- Slicers for dynamic filtering  

These visualizations allow business users to quickly identify churn patterns and customer trends.

---

# Key Insights

- Customers with month-to-month contracts have higher churn rates  
- Customers with shorter tenure are more likely to leave  
- Higher monthly charges increase churn probability  
- Long-term contract customers show higher retention  

---

# Business Impact

This project helps telecom companies:

- Identify high-risk churn customers  
- Improve retention strategies  
- Offer targeted promotions  
- Reduce customer loss  
- Increase revenue and customer lifetime value  

---

# Technologies Used

# Programming & Analysis
- Python  
- Pandas  
- NumPy  

# Visualization
- Matplotlib  
- Seaborn  
- Power BI  

# Machine Learning
- Scikit-learn  
- Logistic Regression  
- Random Forest  
- XGBoost  

# Development Environment
- Jupyter Notebook
