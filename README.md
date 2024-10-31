# Customer Retention Modeling

Customer Retention Analysis and Modeling to Predict Customer Churn

## Overview
This project aims to analyze customer behavior to predict churn in a telecommunications company. By leveraging machine learning techniques, we aim to identify customers at risk of leaving and the primary factors contributing to churn. This analysis can help businesses develop targeted retention strategies.

## Table of Contents
- Project Overview
- Data Source
- Key Findings
- Modeling Insights
- Requirements
- Project Structure
- Usage
- License

## Data Source
The dataset used in this analysis, Telco Customer Churn, is publicly available on Kaggle and contains information about customer demographics, account details, and service usage.

## Key Findings
- **Customer Tenure**: Customers with shorter tenures are at a higher risk of churning, suggesting that new customers may benefit from early engagement initiatives.
- **Monthly Charges**: Higher monthly charges are associated with increased churn, indicating pricing sensitivity among customers.
- **Contract Type and Payment Methods**: Month-to-month contracts and electronic checks are correlated with higher churn rates, highlighting opportunities for loyalty incentives and alternative payment options.

## Modeling Insights
- **Best Model**: The Random Forest model demonstrated an accuracy of 81% and an F1-score of 73% after hyperparameter tuning, making it effective in predicting churn.
- **Key Predictors**: The top predictors of churn were MonthlyCharges, TotalCharges, and tenure, which provide actionable insights for retention strategies.
- **Improvement Opportunities**: The model's performance can be further enhanced by testing additional algorithms, refining features, or adjusting hyperparameters.

## Requirements
To run this project, you'll need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn


## Project Structure
- Customer_Retention_Modeling.ipynb: Jupyter notebook containing the full analysis and modeling process.
- Customer_Retention_Modeling.html: HTML report for easy viewing of the notebook.
- Telco-Customer-Churn dataset.csv: The dataset used for the project.
- README.md: Project description and details.
- LICENSE: License file for the project.
- Install the requirements using:

