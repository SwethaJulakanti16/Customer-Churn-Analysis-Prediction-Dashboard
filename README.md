# 📉 Customer Churn Analysis & Prediction Dashboard

An end-to-end data analytics and machine learning project that identifies key drivers of customer churn and predicts future churners using Power BI, SQL Server, and Python. The solution includes two interactive Power BI dashboards — one focused on **descriptive analytics** and the other on **predictive analytics**, supported by a robust ETL process.

---

## 🎯 Project Objective

To provide business insights into churn behavior and enable proactive retention strategies by:
- Analyzing patterns behind historical churn.
- Forecasting high-risk customers using machine learning.

---

## 📁 Dataset Overview



- **Fields Include**:
  - Customer demographics (Age, Gender, Marital Status)
  - Subscription details (Contract Type, Tenure, Services Used)
  - Payment and revenue data
  - Churn status (Yes/No)
  - Model prediction (Churn Probability, Predicted Status)

---

## 📊 Dashboard Highlights

### 🔍 Churn Summary Dashboard (Descriptive)
- **Purpose**: Diagnose historical churn trends
- **Key Insights**:
  - High churn in Month-to-Month contracts, Fiber Optic users, and Bank Withdrawal payments.
  - Churn more prevalent in customers aged >50.
  - Regional hotspots: Jammu & Kashmir (59.5%), Assam (40.8%).
  - Slicers enabled for filtering by tenure, marital status, and billing.

  ![Image](https://github.com/user-attachments/assets/a0064d07-72b7-48db-a673-4a3fe4e65675)

### 🤖 Churn Prediction Dashboard (ML-Driven)
- **Purpose**: Forecast future churn risk
- **Model**: Random Forest Classifier
- **Insights Delivered**:
  - Identified 378 customers at high risk of churn.
  - Key drivers: Low tenure, Month-to-Month contracts, Credit Card payments.
  - Detailed churn risk profiles integrated with Power BI for retention targeting.


![Image](https://github.com/user-attachments/assets/bf193970-c89e-4666-948e-8bbb6f0f5804)
---

## 🔧 Tools & Technologies Used


- Power BI - Dashboard design & data storytelling 
- SQL Server (SSMS)- ETL, feature engineering, data cleansing 
- Python (Scikit-learn) - ML model training (Random Forest) 
- Excel/CSV - Data source format & exports 

---

## 🧩 ETL Workflow (SQL)

- Cleaned and standardized raw telecom data in SSMS.
- Engineered new features such as `TenureGroup`, `AgeGroup`, and binary encodings.
- Structured data exported to Excel/CSV for further analysis and modeling.

---

## 📎 Business Value

- Enables data-driven retention strategies.
- Combines historical churn analysis with ML-powered forecasting.
- Facilitates actionable insights via interactive visuals and customer-level targeting.

---








