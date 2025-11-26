# Day 7
## 🔁 Preventing Customer Churn with Feature Transformation

A classification model that predicts whether a customer is likely to **leave a subscription-based service**, based on contract type, billing pattern, usage, and tenure.

### 🎯 Goal
Identify high-risk customers early and support retention planning.

### 🔍 Key Findings
- Month-to-month contracts show the highest churn.
- Electronic check billing is a strong churn indicator.
- Short-tenure customers with high monthly charges churn the most.
- Technical support subscription reduces churn likelihood.

### 🛠 Workflow
1. Encode categorical features + scale numerical values
2. Feature transformations (interaction terms, log scaling, binning)
3. Train ML models (Random Forest / Logistic Regression / XGBoost)
4. Evaluate using Accuracy, Precision, Recall, F1-Score & ROC-AUC
