# 🧠 AI-Powered Credit Risk Prediction Project

This project applies machine learning to predict customer credit delinquency using a real-world financial dataset. It compares three models — Logistic Regression, Decision Trees, and Neural Networks — to determine the most accurate and explainable approach for financial risk assessment.

---

## 📌 Objective

To develop a predictive model that can identify customers at risk of credit delinquency, enabling financial institutions to proactively manage collections and reduce default rates.

---

## 📂 Dataset

- **File:** `Delinquency_prediction_dataset.csv`
- **Target Column:** `Delinquent_Account` (Binary classification)
- **Features Used:**
  - `Income`
  - `Credit_Score`
  - `Credit_Utilization`
  - `Missed_Payments`
  - `Debt_to_Income_Ratio`

---

## 🧪 Steps Performed

### 1. Exploratory Data Analysis (EDA)
- Checked for missing values and data types.
- Visualized correlations using heatmaps.
- Summarized numerical and categorical distributions.

### 2. Data Preprocessing
- Handled missing values using **median imputation**.
- Standardized numerical features using **z-score normalization**.

### 3. Model Training
- **Logistic Regression**
- **Decision Tree Classifier**
- **Neural Network (MLPClassifier)**

### 4. Evaluation
- Accuracy scores for all models.
- Classification report and confusion matrix (for Neural Network).
- Visual comparison of model accuracies using a bar chart.

---

## 📊 Results

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| 0.8600 |
| Decision Tree      | 0.6900 |
| Neural Network     | 0.8600 |

- The classification report and confusion matrix provide insights into model performance beyond just accuracy.

---

## 📈 Visual Output

- Heatmaps for:
  - Missing values
  - Correlation between features
- Bar plot comparing model accuracies
<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/a3b98dd9-0a2b-493b-a281-227c855b6920" />

---

## ⚙️ Requirements

Install required libraries with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
