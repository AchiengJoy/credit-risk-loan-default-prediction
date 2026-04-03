# 🏦 Credit Risk / Loan Default Prediction

A machine learning project focused on predicting the probability of loan default using borrower financial, demographic, and repayment-related data.

This project is designed to support **credit risk assessment and lending decision-making** within the banking sector by identifying high-risk borrowers before loan approval.

---

## 📌 Business Problem

Credit risk is one of the most critical areas in banking, as loan defaults directly impact profitability, capital adequacy, and portfolio performance.

The objective of this project is to build a predictive model that can identify borrowers who are likely to default on their loans.

By predicting default risk early, the bank can:

- improve credit approval decisions
- reduce non-performing loans (NPLs)
- support risk-based pricing
- strengthen portfolio quality
- improve profitability

---

## 🎯 Project Objectives

- Perform exploratory data analysis (EDA)
- identify key drivers of default risk
- build predictive classification models
- evaluate model performance
- generate actionable lending recommendations

---

## 📊 Dataset Overview

The dataset contains borrower-level information such as:

- income
- employment status
- loan amount
- loan term
- debt-to-income ratio
- credit history
- repayment status
- loan default label

### Target Variable
> **Default / Loan Status**

This is a **binary classification problem** where:

- `0 = No Default`
- `1 = Default`

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🔍 Exploratory Data Analysis

The EDA focused on identifying patterns that influence loan default risk.

### Key Analysis Areas
- default distribution
- borrower income
- loan exposure
- credit history
- debt burden
- employment stability

### Key Insights
- borrowers with weaker credit history showed higher default probability
- high debt-to-income ratios were associated with increased risk
- larger loan amounts may require tighter risk controls

---

## 🤖 Modeling Approach

The problem was approached as a **supervised machine learning classification task**.

### Models Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📈 Model Performance

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

### Key Focus
For credit risk, **recall is prioritized**, since failing to identify a likely defaulter can result in significant financial loss.

---

## 💡 Business Insights

### 1. Credit History
Borrowers with poor repayment history are significantly more likely to default.

### 2. Debt Burden
High debt-to-income ratio strongly increases repayment risk.

### 3. Loan Exposure
Larger loans should be assessed using stronger risk controls.

---

## 🏦 Banking Use Case

This project is directly applicable to banking environments such as **NCBA** for:

- loan approval decision support
- risk scoring
- credit portfolio monitoring
- default prevention
- early warning systems

This supports data-driven lending strategies and improved risk management.

---

## 🚀 Future Improvements

- hyperparameter tuning
- XGBoost / LightGBM implementation
- probability-based risk scoring
- API deployment using FastAPI / Flask
- dashboard integration in Tableau / Power BI

---

## 👩‍💻 Author

**Joy Achieng Odhiambo**  
Data Scientist 
GitHub: https://github.com/AchiengJoy
