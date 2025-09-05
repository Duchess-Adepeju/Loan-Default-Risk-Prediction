# Loan-Default-Risk-Prediction
This repository contains the full code for my end-to-end machine learning pipeline that predicts loan default risk, featuring data cleaning, feature engineering, SMOTE balancing, CatBoost modeling, and deployment with Streamlit.
## Project Overview  
Traditional credit scoring often fails to capture the full picture of borrower behavior.  
This project builds a robust pipeline to predict defaults more accurately by:  
- Cleaning and unifying borrower demographics, loan performance, and past loan data.  
- Engineering behavioral features such as repayment delays and repayment ratios.  
- Tackling class imbalance with **SMOTE**.  
- Comparing multiple models and selecting **CatBoost** for its superior recall and ROC AUC.  
- Deploying the final model with **Streamlit** for real-time use.  

## Key Features  
- **Data Cleaning & Feature Engineering** – turning raw loan data into meaningful borrower insights.  
- **SMOTE Oversampling** – addressing class imbalance to better capture defaults.  
- **Modeling & Evaluation** – Logistic Regression, Random Forest, Gradient Boosting, and CatBoost.  
- **Deployment** – interactive predictions with Streamlit + ngrok.  
