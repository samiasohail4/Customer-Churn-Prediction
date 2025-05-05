# Customer Churn Prediction

## 📊 Project Overview

This project focuses on analyzing customer churn data for a telecom company to identify patterns that lead to customer attrition and predict which customers are likely to leave. It uses machine learning to help businesses take proactive measures to retain customers.

## 🧠 Problem Statement

Churn refers to the loss of customers over time. Telecom companies face significant revenue losses when customers leave. By analyzing churn patterns, we can build a model that accurately predicts whether a customer is likely to churn, allowing targeted interventions.

## 📁 Dataset

- **Source**: [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Records**: 7,043 customer records
- **Features**: Demographics, services, account information, and churn status

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn (Logistic Regression, Pipelines, Evaluation Metrics)
- Jupyter Notebook / VS Code

## 🧪 Workflow

1. Data Loading & Cleaning  
2. EDA (Exploratory Data Analysis)  
3. Feature Engineering  
4. Preprocessing Pipeline (Numerical + Categorical)  
5. Model Training using Logistic Regression  
6. Evaluation using Accuracy and AUC Score  
7. Conclusion & Business Recommendations  

## ✅ Results

- **Test Accuracy**: 82.6%  
- **AUC Score**: 0.86  
- **Model**: Logistic Regression with scikit-learn pipeline

## 🔍 Key Insights

- Customers with **short tenure** and **high monthly charges** are more likely to churn.
- **Contract type**, **payment method**, and **internet service** are strong churn predictors.
- **Paperless billing** is more common among churned users.
- The logistic regression model performed meaningfully well for this classification task.

## 🧾 Conclusion

This project demonstrates a complete end-to-end machine learning pipeline to solve a real-world business problem using data analysis and logistic regression. It highlights how predictive modeling can help reduce churn by identifying high-risk customers in advance.

