# Telecom Customer Churn Analysis Dashboard

Power BI dashboard analyzing customer churn patterns using DAX measures and Power Query data cleaning.

📊 Overview
This project analyzes churn behavior for a telecom company's customer base (7,043 customers) to identify key drivers of customer attrition and highlight actionable retention opportunities.

🎯 Key Insights
- Overall churn rate: 26.5% — roughly 1 in 4 customers leave
- Contract type is the biggest driver — month-to-month customers churn far more than annual contract customers
- Fiber optic internet users churn more than DSL or no-internet customers
- Electronic check payment users show the highest churn rate compared to automatic payment methods
- Most churn happens within the first few months** of tenure — highlighting onboarding as a critical retention window

 🛠️ Tools & Techniques
-Power Query: Data cleaning — removed duplicates, fixed data types, handled blank/error values in TotalCharges
- DAX Measures: Built using COUNTROWS, CALCULATE, and DIVIDE functions to calculate Total Customers, Churned Customers, and Churn Rate %
-Visualizations: KPI cards, clustered column charts, and line charts to build a clear data story

 📁 Dataset
Public Telco Customer Churn dataset (IBM sample data), sourced from Kaggle:
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

 📸 Dashboard Preview
 <img width="1180" height="713" alt="image" src="https://github.com/user-attachments/assets/b54c7fa7-e92b-4038-a22d-100bfd2d2f1c" />


