# Telco Customer Churn Analysis

This project explores customer churn prediction for a telecommunications company using demographic, service usage, and contract data.

## Objective
- Predict customer churn under class imbalance
- Segment customers by churn risk to support targeted retention strategies

## Approach
- Exploratory data analysis (EDA)
- Logistic regression pipeline with preprocessing
- Model evaluation using F1 score and ROC-AUC
- Threshold tuning and risk segmentation

## Key Results
- F1 score: ~0.67
- ROC-AUC: ~0.88
- Clear separation across risk segments (Low → Very High)

## Files
- `notebooks/`: analysis notebook
- `models/churn_model.pkl`: final trained pipeline
- `data/`: dataset

