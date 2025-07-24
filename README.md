# 🧠 AI-Powered Credit Risk Prediction Project

This project explores the use of machine learning to predict credit delinquency risk using customer financial data. Built as part of a virtual internship with **Tata iQ on Forage**, this system demonstrates a responsible, data-driven approach to identifying high-risk customers.

---

## 📊 Project Overview

In the financial services sector, identifying and proactively managing delinquent accounts is crucial. This ML-powered solution leverages customer credit data to:

- Predict likelihood of delinquency using classification models.
- Identify high-risk segments using exploratory data analysis (EDA).
- Compare model performances and visualize insights.
- Support responsible, ethical financial decision-making.

---

## 📁 Dataset Summary

The dataset contains anonymized customer-level financial features such as:

- `Income`
- `Credit_Score`
- `Credit_Utilization`
- `Missed_Payments`
- `Debt_to_Income_Ratio`
- `Delinquent_Account` *(Target variable)*

### 🔥 Missing Values Heatmap

![Missing Values](https://github.com/bhargavkoushik/AI-Powered-Credit-Risk-Prediction-Project/blob/main/assets/missing_values_heatmap.png)

---

## 📌 Key Correlations

- Moderate positive correlation between `Missed_Payments` and `Delinquent_Account`.
- High credit utilization and low income were found as strong indicators of delinquency.

### 📉 Correlation Matrix

![Correlation Matrix](https://github.com/bhargavkoushik/AI-Powered-Credit-Risk-Prediction-Project/blob/main/assets/correlation_matrix.png)

---

## 🧪 Models Trained

The following models were trained and evaluated:

| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression | ✅ 0.81   |
| Decision Tree       | ✅ 0.87   |
| Neural Network (MLP)| ✅ 0.83   |

### 📊 Accuracy Comparison

![Model Accuracy Comparison](https://github.com/bhargavkoushik/AI-Powered-Credit-Risk-Prediction-Project/blob/main/assets/model_accuracy_comparison.png)

---

## 📌 Technologies Used

- Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- Git + GitHub

---

## 🧠 Learnings & Outcome

- Identified top risk factors for credit delinquency.
- Developed explainable models suitable for stakeholder presentation.
- Practiced responsible AI and ethical model deployment thinking.
- Completed a structured business report and autonomous system framework.

---

About
This project was built as part of the Tata iQ x Forage Virtual Internship Program, simulating real-world responsibilities in AI consulting, ML modeling, and ethical system design.
