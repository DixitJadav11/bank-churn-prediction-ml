# bank-churn-prediction-ml
End-to-end Machine Learning project predicting customer churn in banking using advanced classification algorithms and hyperparameter tuning.
# 💼 Bank Churn Prediction using Machine Learning

This project predicts customer churn in a bank using multiple machine learning models. The goal is to help the bank proactively retain customers and reduce revenue loss.

## 📌 Objective
Predict whether a customer will churn or not based on past banking records.

## 📊 Dataset
- 10,000+ records
- 14 features: Age, Credit Score, Balance, Tenure, Geography, Gender, etc.
- Target: `Exited` (1 = Churned, 0 = Stayed)

## 🧪 Tools & Libraries Used
- Python
- Pandas, Seaborn, Matplotlib
- Scikit-learn, XGBoost, LightGBM, RandomForest
- SMOTE, GridSearchCV

## 🔍 Exploratory Data Analysis
- Outlier treatment using IQR
- Univariate & Bivariate visualizations
- Handled imbalance using SMOTE
- No multicollinearity (all VIF < 5)

## 🛠️ Feature Engineering
- Dropped irrelevant features
- Label Encoding + Standardization
- Feature selection using Random Forest importance

## 🧠 Models Used
- Logistic Regression
- Random Forest
- XGBoost
- LightGBM ✅ *(Best performer)*

## 🏆 Final Results (Tuned LightGBM)
- Accuracy: **83%**
- Precision: **71%**
- Recall: **76%**
- F1 Score: **73%**
- AUC Score: **0.85**

## 📈 Business Insight
- Older customers with high balances and low engagement are most likely to churn.
- Gender & geography show moderate effects.

## 📁 Files Included
- `Bank_Churn_Prediction.ipynb` – Full code
- `Bank_Churn_Prediction_Presentation_Dixit_Jadav.pptx` – Slide deck summary
- [Bank_Churn_Prediction_Presentation_Dixit_Jadav.pptx]– Downloadable slide deck
- `README.md` – Project overview

## 👨‍💻 Author
**Dixit Jadav**  
📍 [LinkedIn](https://www.linkedin.com/in/dixit-jadav-30ba08301)
