# Credit Card Fraud Detection — Capstone Project

End-to-end ML pipeline for detecting credit card fraud on 1.29M transactions 
(0.58% fraud rate) using XGBoost, SHAP interpretability, and imbalanced-class 
handling.

## Results
| Metric | Score |
|--------|-------|
| ROC-AUC | 0.996 |
| PR-AUC | 0.851 |
| Recall (Fraud) | 84.7% |
| Net Savings (Test) | $347,880 |
| ROI | 22.4x |

## Tech Stack
Python · XGBoost · SHAP · scikit-learn · pandas · Matplotlib · SMOTE

## Project Structure
- `Credit_Fraud_Detection_Capstone_Project_Yuktha.ipynb` — full notebook
- Dashboard: in progress

## Dataset
Synthetically generated credit card transactions (Kaggle — Sparkov tool), 
Jan 2019 – Dec 2020, 1,000 customers × 800 merchants.
