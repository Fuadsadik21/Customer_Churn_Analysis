# Customer Churn Analysis

*Predicting customer churn using machine learning—all in one notebook.*

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Key Features](#key-features)
3. [Dataset](#dataset)
4. [Workflow](#workflow)
5. [Results](#results)
6. [How to Use](#how-to-use)
7. [Technologies Used](#technologies-used)
8. [Future Work](#future-work)
9. [Contact](#contact)

---

## Project Overview
This project aims to predict customer churn and identify key drivers of attrition using machine learning. By analyzing customer behavior, we can provide actionable insights to help businesses reduce churn and improve retention. The entire workflow—from EDA to model interpretability—is implemented in a single Jupyter notebook.

---

## Key Features
- **Exploratory Data Analysis (EDA)**: Analyzed customer data to identify trends and patterns.
- **Predictive Modeling**: Built and compared multiple models (Logistic Regression, Random Forest, XGBoost).
- **Model Interpretability**: Used feature importance and partial dependence plots to explain predictions.
- **Actionable Insights**: Provided recommendations to reduce churn.

---

## Dataset
The dataset used is the [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn). It includes 7,043 customers with 21 features, such as:
- **Monthly Charges**: The amount charged to the customer monthly.
- **Tenure**: The number of months the customer has stayed with the company.
- **Contract Type**: The type of contract (month-to-month, one year, two years).

---

## Workflow
The project is divided into four phases, all implemented in one notebook:
1. **Exploratory Data Analysis (EDA)**: Cleaned the data, handled missing values, and created new features.
2. **Baseline Modeling**: Built a Logistic Regression model as a baseline.
3. **Advanced Modeling**: Compared Random Forest, XGBoost, and SVM models.
4. **Model Interpretability**: Explained predictions using feature importance and partial dependence plots.

---

## Results
- **Best Model**: Random Forest achieved an ROC-AUC of 0.85 and an F1-score of 0.72.
- **Key Insights**: Higher monthly charges and shorter tenure increase churn probability.
- **Recommendations**: Offer discounts, loyalty rewards, and budget-friendly plans.

---

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-churn-analysis.git
   cd customer-churn-analysis
