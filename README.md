# Customer Churn Analysis – Telecom Dataset

## Project Overview
This project analyzes telecom customer data to understand why customers leave (churn) and what factors influence their decisions. The goal is to help telecom companies identify high-risk customers, improve service retention strategies, and reduce churn rates using data-driven insights.

## Objectives
- Identify factors that contribute most to customer churn  
- Analyze churn distribution across demographics and services  
- Study the relationship between contract type, monthly charges, tenure, and churn  
- Provide actionable insights to improve customer retention  

## Dataset
- File: WA_Fn-UseC_-Telco-Customer-Churn.csv  
- Source: Kaggle (Telecom Customer Churn Dataset)  
- Key Columns:  
  customerID, gender, tenure, InternetService, MonthlyCharges,  
  TotalCharges, Contract, PaymentMethod, Churn

## Tools and Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

## Steps Performed
1. Data Loading and Inspection  
2. Data Cleaning (handling missing values, correcting data types, removing duplicates)  
3. Feature Engineering (tenure groups, charge categories, categorical encodings)  
4. Exploratory Data Analysis (churn patterns across services and demographics)  
5. Visualizations (bar charts, histograms, boxplots, heatmaps)  
6. Insights and Business Recommendations  

## Key Insights
- Monthly charges are significantly higher among customers who churn.  
- Short-term contracts (Month-to-Month) show the highest churn rate.  
- Customers using fiber optic internet churn more frequently.  
- Customers paying via electronic check churn at higher rates.  
- Long-term customers (high tenure) are much less likely to churn.

## Business Recommendations
- Offer discounts or incentives to high-charge and month-to-month customers.  
- Improve fiber optic service quality to reduce customer dissatisfaction.  
- Promote auto-pay or bank transfer payment methods.  
- Develop loyalty programs for medium-tenure customers to prevent churn.

## Requirements
Run the following command to install required libraries:
