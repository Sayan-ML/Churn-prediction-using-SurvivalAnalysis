# 📊 Customer Churn Analysis with Survival Modeling & Machine Learning  

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)  
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-XGBoost%20%7C%20Scikit--learn-orange?logo=keras)](https://scikit-learn.org/stable/)  
[![Survival Analysis](https://img.shields.io/badge/Survival%20Analysis-Lifelines-red)](https://lifelines.readthedocs.io/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![Made with Love](https://img.shields.io/badge/Made%20with-Love-ff69b4)]()  

---

## 🔍 Project Overview  

Customer churn is one of the most critical business challenges in subscription-based industries. Companies lose substantial revenue when customers discontinue their services, making **churn prediction and prevention strategies essential**.  

This project combines the **temporal insights of Survival Analysis** with the **predictive power of Machine Learning** to provide a holistic view of churn behavior.  

### ✅ Objectives
- Understand **time-to-churn dynamics** across customer groups.  
- Identify the **most influential features** contributing to churn.  
- Build **statistical survival models** (Kaplan-Meier, Cox Proportional Hazards) for temporal risk assessment.  
- Develop **ML classifiers** (XGBoost, Random Forest, Logistic Regression) for churn prediction.  
- Deliver **actionable business insights** for churn reduction strategies.  

---

## 🛠️ Technologies & Tools  

- **Python:** Data preprocessing, modeling, and analysis  
- **Lifelines:** Kaplan-Meier survival curves, Cox Proportional Hazards Model  
- **Scikit-learn:** Data preprocessing, feature selection, classification models  
- **XGBoost:** Gradient boosting for churn classification  
- **Matplotlib & Seaborn:** EDA, churn visualization, and survival plots  

---

## 📈 Key Insights  

- 📉 **Churn timeline:** Most churn happens within the **first 10 months** of customer tenure.  
- 📑 **Customer contracts:** Short-term contracts exhibit significantly higher churn rates than long-term ones.  
- 💳 **Payment methods:** Electronic check users churn more often compared to those using auto-payments.  
- ⚖️ **Non-proportional hazards:** Stratified Cox modeling helped adjust features violating assumptions.  
- 🎯 **ML performance:** Achieved **87% accuracy** and **82% F1 score** using **XGBoost**, outperforming other models.  

---

## 📂 Project Structure  

```bash
├── data/                  # Raw and preprocessed datasets
├── notebooks/             # Jupyter notebooks for EDA, survival analysis, and ML
├── models/                # Trained model files (optional, e.g. XGBoost, Cox model)
├── plots/                 # Visualizations (KM curves, hazard functions, etc.)
├── src/                   # Utility functions and helper scripts
│   ├── preprocess.py
│   ├── survival_models.py
│   ├── ml_models.py
├── requirements.txt       # Dependencies
└── README.md              # Documentation
```

---

## 🚀 Future Improvements  

- [ ] Extend dataset to include **real-time customer interaction logs**.  
- [ ] Incorporate **Deep Learning Survival Models** (DeepSurv, RNN-based).  
- [ ] Experiment with **Explainable AI (SHAP, LIME)** to enhance interpretability.  
- [ ] Deploy as a **Streamlit or Flask web app** for real-time churn prediction.  
- [ ] Automate periodic **retraining pipelines** with MLOps tools (MLflow, Airflow).  

---

## 🤝 Contributing  

Contributions are welcome! 🎉  

1. Fork the repository  
2. Create a new branch (`feature-new`)  
3. Commit your changes  
4. Push the branch  
5. Submit a Pull Request  

---

## 👨‍💻 Developed By  

**Sayan Banerjee**  
🎓 MSc in Statistics & Computing, BHU  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sayan%20Banerjee-blue?logo=linkedin)](https://www.linkedin.com/in/sayan-ban-005/)  
[![GitHub](https://img.shields.io/badge/GitHub-SayanBanerjee-black?logo=github)](https://github.com/sayanbanerjee)  

---

## 💖 Show Your Support  

If you found this project helpful:  
⭐ Star the repo  
🔗 Share with your network  
💬 Suggest improvements  

---

## 📄 License  

This project is licensed under the **MIT License** – feel free to use, modify, and distribute with proper attribution.  

---

