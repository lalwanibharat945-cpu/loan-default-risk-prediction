# 🏦 Loan Default Risk Prediction

## 📌 Overview
This project focuses on predicting whether a customer will default on a loan using financial, demographic, and historical loan data.

The goal is to help financial institutions identify high-risk customers and reduce potential losses.

---

## 💼 Business Problem
Loan defaults lead to significant financial losses. The challenge is to accurately identify risky customers in a highly imbalanced dataset (~8% default rate).

---

## 📂 Dataset
- Application Data (customer info)
- Previous Loan Data (historical behavior)

Target:
- 1 → Default
- 0 → No Default

---

## ⚙️ Key Steps

### 🧹 Data Cleaning
- Handled missing values
- Fixed anomalies (e.g., DAYS_EMPLOYED issue)
- Treated outliers

### ⚙️ Feature Engineering
- Annuity Burden
- Income to Credit Ratio
- Previous loan aggregation

### 🤖 Modeling
- Logistic Regression (final model)
- Random Forest (tuned & compared)

---

## 📊 Results

| Metric | Value |
|-------|------|
| Recall (Default) | ~0.68 |
| Precision | ~0.16 |
| ROC-AUC | ~0.74 |

---

## 🧠 Key Insights

- Credit history (EXT_SOURCE) is the strongest predictor  
- Financial burden impacts default risk  
- Employment stability matters  

---

## 💼 Business Recommendations

- Focus on customers with poor credit scores  
- Monitor high annuity burden  
- Flag unstable employment  

---

## 🚀 Future Improvements

- Try XGBoost  
- Deploy model using Flask  
- Build interactive dashboard  

---

## 📌 Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## 👤 Author
Your Name  
