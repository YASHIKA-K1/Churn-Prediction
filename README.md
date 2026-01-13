**Customer Churn Prediction**

**Overview**

This project builds a machine learning–based churn prediction system to identify customers who are likely to leave a telecom service. The goal is to support data-driven retention strategies and reduce customer attrition.

**Dataset**

- Telecom customer dataset containing demographic, service usage, and billing details
- Target variable: Churn (Yes / No)

**Methodology**

- Performed data cleaning and exploratory data analysis (EDA) to understand churn patterns.
- Conducted feature encoding and preprocessing to prepare data for modeling.

**Trained and evaluated multiple models:**

- Logistic Regression
- Random Forest
- Logistic Regression with Class Weights
- Tuned Random Forest
- XGBoost

Evaluated models using Accuracy, Precision, Recall, and F1-score.

**Results**

- Model	Accuracy
- Logistic Regression	79%
- Random Forest	78%
- Logistic Regression (Class Weighted)	79%
- Tuned Random Forest	79%
- XGBoost	77%

**Key takeaway:**

The best-performing models achieved ~79% accuracy, with class-weighted and tuned models improving the model’s ability to correctly identify churn customers, making them more suitable for real-world retention use cases.

**Business Impact**

- By predicting customers at high risk of churn, this system enables:
- Targeted retention campaigns
- Reduced customer acquisition costs
- Improved customer lifetime value

Tech Stack

Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn
