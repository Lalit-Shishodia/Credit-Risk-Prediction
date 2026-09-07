# Business Problem

A bank/NBFC receives thousands of loan applications. The objective is to predict whether an applicant is likely to default on a loan.

# Business objective: Build a machine-learning system that predicts:


Loan Applicant
      ↓
Credit / Financial Information
      ↓
Data Processing
      ↓
Feature Engineering
      ↓
ML Model
      ↓
Probability of Default
      ↓
Risk Classification
      ↓
LOW / MEDIUM / HIGH RISK
----------------------------------------------------------------------------------------------------------------------------------

                    CREDIT RISK PREDICTION
                             │
             ┌───────────────┴───────────────┐
             ↓                               ↓
       Customer Data                   Loan Data
             │                               │
             └───────────────┬───────────────┘
                             ↓
                       SQL DATABASE
                             ↓
                    Data Extraction
                             ↓
                         Python
                             ↓
                  Data Cleaning & EDA
                             ↓
                    Feature Engineering
                             ↓
                 Train / Validation / Test
                             ↓
              ┌──────────────┴──────────────┐
              ↓                             ↓
       Logistic Regression             Random Forest
              ↓                             ↓
         XGBoost / LightGBM (optional)
              └──────────────┬──────────────┘
                             ↓
                    Model Evaluation
                             ↓
              Probability of Default
                             ↓
                    Risk Classification
                             ↓
            ┌────────────────┴───────────────┐
            ↓                                ↓
       Streamlit App                    Power BI
            ↓                                ↓
     Credit Prediction             Portfolio Analytics
