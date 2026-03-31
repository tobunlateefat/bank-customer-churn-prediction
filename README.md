# Predicting Bank Customer Churn Using Machine Learning
A comparison between Logistic Regression, Random Forest and Gradient Boosting. Built with Python, Scikit-learn and SMOTE for class balancing.

## Overview
Customer churn is a critical challenge for financial institutions. Acquiring a new bank customer costs 5–7 times more than retaining an existing one. This project builds and compares machine learning models to identify customers at risk of churning, enabling proactive retention strategies.

## Research Aim
To identify and predict bank customers at risk of churning using machine learning, enabling financial institutions to implement data-driven retention strategies.

## Research Objectives
- Explore key factors influencing bank customer churn
- Build and compare multiple ML models for churn prediction
- Identify the most accurate algorithm for real-world deployment
- Provide data-driven recommendations for customer retention

## Research Questions
- What demographic and behavioural factors predict bank customer churn?
- Which machine learning algorithm most accurately predicts churn?
- How can banks use predictive analytics to reduce customer attrition?

## Dataset
- Source: Bank Customer Churn Prediction Dataset (Kaggle)
- 10,000 customer records across France, Germany and Spain
- 20.37% churn rate
- Features include credit score, geography, gender, age, tenure, balance, and activity status

## Key Findings from Exploratory Analysis
- Female customers churn at a significantly higher rate than male customers
- Germany has the highest churn rate by geography — nearly double that of France and Spain
- Active members churn at a much lower rate than inactive members

## Models Compared

| Model | Churn Precision | Churn Recall | Churn F1 | ROC-AUC |
|-------|----------------|--------------|----------|---------|
| Logistic Regression | 0.38 | 0.72 | 0.50 | 0.71 |
| Random Forest | 0.62 | 0.58 | 0.60 | 0.74 |
| Gradient Boosting | 0.58 | 0.67 | 0.62 | 0.77 |

## Conclusion
Gradient Boosting delivers the best overall performance with the highest ROC-AUC (0.77) and F1-score (0.62). The model correctly identified 271 out of 407 churning customers in the test set. In a production banking environment, this model would enable targeted retention campaigns saving significant revenue.

## Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, Imbalanced-learn, Matplotlib, Seaborn

## Author
**Lateefat Tobun** — MSc Applied AI & Data Analytics (Distinction), University of Bradford
