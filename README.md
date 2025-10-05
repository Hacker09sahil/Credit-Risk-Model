# Credit-Risk-Model
End-to-end Credit Risk Modeling project for FinTech applications — includes data preprocessing, feature engineering, model training (XGBoost), evaluation, and insights for predicting loan default probability.


## 🚀 Project Overview
- **Goal:** Predict whether a loan applicant will default.
- **Data:** Kaggle - Home Credit Default Risk (kept out of repo; see Data section).
- **Models:** Logistic Regression, Random Forest, XGBoost (final).
- **Deployment:** Local demo app (Streamlit) — optional.

---

## 📁 Repository Structure
credit-risk-modeling/
├── data/ # (not tracked) store raw/processed CSVs here
├── notebooks/ # Jupyter notebooks (EDA, feature engineering, training)
├── src/
│ ├── data_preprocessing.py
│ ├── features.py
│ ├── train_model.py
│ └── predict.py
├── models/
│ └── xgb_credit_model.pkl # (optional - use Git LFS or cloud storage for large files)
├── credit_risk_app.py # Streamlit app for local demo
├── requirements.txt
├── .gitignore
└── README.md
