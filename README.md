# Customer Churn Prediction Using Machine Learning

## Overview

This project develops and evaluates machine learning models to predict customer churn using the IBM Telco Customer Churn dataset. The objective is to identify customers who are likely to leave the company and to derive actionable business insights that can improve customer retention.

---

## Problem Statement

Customer churn is a major challenge for telecommunication companies. Predicting churn enables businesses to proactively retain customers and reduce revenue loss.

This project aims to:

* Predict whether a customer will churn.
* Compare multiple machine learning models.
* Identify the factors influencing churn.
* Generate business recommendations based on model interpretation.

---

## Dataset

Dataset: IBM Telco Customer Churn Dataset

Features include:

* Customer demographics
* Internet services
* Contract type
* Payment method
* Monthly charges
* Total charges
* Customer tenure

Target Variable:

* Churn (Yes/No)

---

## Project Workflow

1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Train-Test Split
5. Feature Scaling
6. Logistic Regression
7. Decision Tree
8. Random Forest
9. Cross Validation
10. Hyperparameter Tuning
11. Model Comparison
12. Model Interpretation
13. Business Recommendations

---

## Models Used

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

Hyperparameter tuning was performed using GridSearchCV.

---

## Model Performance

| Model               | Cross-Validated ROC-AUC |
| ------------------- | ----------------------- |
| Logistic Regression | 0.846                   |
| Tuned Random Forest | 0.845                   |
| Tuned Decision Tree | 0.827                   |

Logistic Regression achieved the highest cross-validated ROC-AUC and was selected as the final model.

---

## Key Findings

* Customer tenure was the strongest predictor of churn.
* Long-term contracts reduced churn probability.
* Fiber optic customers exhibited higher churn tendencies.
* Online security and technical support services improved customer retention.
* Electronic check payments and paperless billing were associated with higher churn rates.

---

## Business Recommendations

* Focus retention efforts on new customers.
* Encourage customers to adopt long-term contracts.
* Improve customer experience for fiber optic users.
* Promote value-added services such as online security and technical support.
* Review billing and payment processes.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

---

## Repository Structure

```
Customer-Churn-Prediction/
│
├── data/
├── images/
├── models/
├── Customer_Churn_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## Conclusion

This project demonstrates how machine learning can be used not only for prediction but also for generating interpretable insights that support customer retention strategies.
