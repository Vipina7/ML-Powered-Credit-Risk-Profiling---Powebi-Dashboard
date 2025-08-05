# 🧾 Credit Card Default Risk Analysis and Dashboard

This project aims to identify high-risk credit card customers using a Random Forest model, and present key insights through an interactive Power BI dashboard to support data-driven credit risk strategies.

---

## 🚀 Project Overview

- **Dataset**: 30,000 credit card customer records (including repayment history, credit limit, education, marital status, etc.)
- **Objective**: Predict likelihood of customer default in the upcoming month.
- **Tools Used**: 
  - `Python` (pandas, scikit-learn, GridSearchCV)
  - `Power BI` for interactive dashboarding and storytelling
- **Target Output**: A comprehensive dashboard highlighting customer risk tiers, default probability, and key driver analysis.

---

## 🧠 Machine Learning Model

- **Model Used**: Random Forest Classifier
- **Preprocessing**: 
  - Feature importance selection
  - Standardization
  - Binning (Credit Limit, Age Groups)
- **Tuning**: GridSearchCV for optimal hyperparameters
- **Evaluation Metrics**:
  - Accuracy: ~76%
  - ROC AUC: ~0.71
  - F1 Score (High Risk Class): ~0.45

---

## 📊 Dashboard Features (Power BI)

### ✅ Credit Risk Overview
- Total customers, default rate, high-risk percentage
- Risk tier distribution (High / Medium / Low)
- Default rate by education, marital status, gender
- Credit limit vs default probability
- Top drivers of default from the ML model

### ⚠️ Top Risk Drivers
- Default rate across repayment statuses (Jul, Aug, Sep)
- Default probability across credit limit bins
- Dynamic filters by gender, age group, education, marital status

### 👤 Customer Drill-Down
- Conditional formatting by risk tier and predicted default probability
- Full demographic and financial details per customer
- Interactive filtering by all dimensions

---

## 📁 Folder Structure

/CreditCard-Default-Risk/
├── data
    ├── credit_default_risk_dashboard.csv
    ├── default of credit card clients.xls
├── icons
    ├── home.png
    ├── private-detective.png
    ├── risk-management.png
├── PowerBI_Dashboard.pbix
├── README.md
└── requirements.txt

---
## 📎 License

This project is for academic and demonstration purposes only.  
Feel free to fork and customize for your own case studies or portfolios.