# 📊 Customer Churn Analysis with Survival Modeling & Machine Learning

This project focuses on understanding and predicting customer churn using a combination of **Survival Analysis** and **Classical Machine Learning** techniques. The goal was to uncover temporal churn patterns and build a robust predictive model.

---

## 🔍 Overview

- Performed a detailed **Exploratory Data Analysis (EDA)** to identify key drivers of churn.
- Used **Kaplan-Meier (KM) survival curves** to analyze time-to-churn behavior across customer segments.
- Fitted a **Stratified Cox Proportional Hazards Model** to account for non-proportional covariate effects and uncover how churn risk changes over time.
- Built and evaluated various **classification models** to predict churn status.
- Achieved an **87% accuracy** and **82% F1 score** using **XGBoost**.

---

## 🛠️ Technologies & Tools

- Python (Pandas, NumPy, Scikit-learn)
- Lifelines (Survival Analysis)
- XGBoost
- Matplotlib & Seaborn (Visualization)

---

## 📈 Key Insights

- Most churn occurs within the **first 10 months** of customer tenure.
- Survival probabilities vary significantly across **contract types** and **payment methods**.
- Stratified Cox modeling helped adjust for features violating the proportional hazard assumption.
- Early intervention strategies should target customers in their **first year of service**.

---

## 📁 Project Structure


