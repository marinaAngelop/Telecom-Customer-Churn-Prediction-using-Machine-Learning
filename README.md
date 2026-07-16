# Customer Churn Prediction

## Project Overview

This project develops and evaluates machine learning models to predict customer churn in a telecommunications company. The goal is to identify customers who are likely to leave the company and provide business insights that support customer retention strategies.

---

## Dataset

- **Source:** Kaggle
- **Records:** 7,043 customers
- **Target Variable:** Churn Value (0 = No Churn, 1 = Churn)

---

## Project Workflow

- Data Loading
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Logistic Regression
- Random Forest
- Hyperparameter Tuning
- Cross Validation
- Feature Importance
- SHAP Explainability
- Business Insights

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SHAP

---

## Machine Learning Models

- Logistic Regression
- Random Forest
- Tuned Random Forest

---

## Results

- Logistic Regression achieved the best Recall for identifying customers at risk of churn.
- Hyperparameter tuning improved the performance of the Random Forest model.
- SHAP analysis confirmed that **Tenure Months**, **Contract Type**, **Monthly Charges**, and **Total Charges** were the most influential features.

---

## Business Insights

- Customers with shorter tenure are more likely to churn.
- Month-to-month contracts are associated with higher churn risk.
- Higher monthly charges increase the probability of churn.
- Customers without Online Security or Technical Support are more likely to leave.
- These insights can help companies develop targeted customer retention strategies.

---

## Repository Structure

```
customer-churn-prediction/
│
├── Customer_Churn_Prediction.ipynb
└── README.md
```

---

## Future Improvements

- Evaluate additional machine learning models (e.g., XGBoost, LightGBM).
- Handle class imbalance using SMOTE.
- Deploy the model as a web application.
