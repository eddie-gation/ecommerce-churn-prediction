# E-Commerce Customer Churn Prediction

## Overview
This project builds a machine learning model to predict customer churn 
in an e-commerce platform and quantifies the financial impact of 
retention campaigns through cost-benefit analysis.

## Business Problem
Customer churn directly translates to revenue loss. By identifying 
high-risk customers in advance, the business can intervene with targeted 
retention campaigns before churn occurs.

**Key Questions:**
- Which customers are likely to churn?
- At what threshold does the retention campaign maximize cost savings?

## Results
| | Value |
|---|---|
| Best Model | XGBoost |
| AUC | 0.9869 |
| Optimal Threshold | 0.11 |
| Cost Saving vs No Model | 35,460 USD (95.8%) |

## Key Findings
- Tenure is the strongest predictor — newer customers churn significantly more
- Customers who filed complaints are more likely to churn
- Single customers and Mobile Phone buyers show higher churn rates

## Project Structure
ecommerce_churn/
├── E_Commerce.ipynb
└── README.md

## Tech Stack
- Python 3.13
- pandas, numpy, matplotlib, seaborn
- scikit-learn, xgboost
