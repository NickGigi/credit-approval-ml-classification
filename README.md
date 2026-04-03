# Credit Approval ML Classification

## Overview
Supervised machine learning project built for a financial institution to predict whether a credit application will be approved or rejected, using Logistic Regression and Decision Tree classifiers.

## Objective
- Prepare and clean a real-world credit dataset
- Train and evaluate two classification models
- Compare results and draw business conclusions

## Key Steps
1. Data cleaning — handled invalid entries, case inconsistencies, and null values
2. Outlier detection — removed outliers using the IQR method
3. Encoding — One-Hot Encoding for nominal variables, manual ordinal mapping for ranked variables
4. Model training — Decision Tree and Logistic Regression
5. Evaluation — classification reports and confusion matrices

## Key Findings
- Features like Credit Score, Risk Category, and Debt-to-Income Ratio were the strongest predictors of credit approval
- Logistic Regression generalizes better and is less prone to overfitting
- Decision Tree offers higher interpretability, valuable for regulatory compliance in financial settings

## Technologies Used
- Python, Pandas, Scikit-learn, Matplotlib, Seaborn

## Dataset
- Credit dataset (Excel format): customer demographic, financial, and behavioral data
- Target variable: Granted (1 = Approved, 0 = Rejected)
