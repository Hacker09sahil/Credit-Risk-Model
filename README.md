# Create README.md
echo "# Credit Risk Modeling
End-to-end Credit Risk Modeling project for FinTech applications — includes data preprocessing, feature engineering, model training (XGBoost), evaluation, and insights for predicting loan default probability.

## 🚀 Project Overview
- Predict loan default risk using Kaggle’s Home Credit dataset.
- Includes preprocessing, feature engineering, model training, evaluation, and visualization.

## 🧠 Tech Stack
Python, pandas, scikit-learn, XGBoost, Streamlit, Matplotlib, Seaborn

## 📊 Model
Final model: XGBoost
- Accuracy: ~85%
- ROC-AUC: 0.90
- F1-score: 0.81

## 📁 Structure
📦 credit-risk-modeling
├── data/ (not uploaded)
├── notebooks/
├── models/
├── src/
├── requirements.txt
├── README.md
└── .gitignore

## 📬 Author
Sahil Tiwari — NIT Raipur
" > README.md

# Create requirements.txt
echo "pandas
numpy
scikit-learn
xgboost
matplotlib
seaborn
streamlit
imbalanced-learn
shap" > requirements.txt

# Create .gitignore
echo "__pycache__/
venv/
.env
*.csv
*.zip
data/
models/
.ipynb_checkpoints/
*.pkl
.DS_Store
Thumbs.db" > .gitignore





