# Sterling Trust Bank – Customer Churn & Retention Analytics Dashboard

An end-to-end Power BI project analyzing customer churn and retention for a private-sector bank. The project uses a Star Schema data model, Power Query for data transformation, and DAX for analytical measures and KPIs.

# Dashboard Pages

# 1. Churn Overview
- Overall customer, churn, and retention KPIs
- Monthly churn trends
- Churn analysis by geography
- Membership analysis

# 2. Customer Demographics
- Customer exits by credit card status
- Churn by geography
- Churn by gender
- Demographic-based customer analysis

# 3. Churn Factors
- Churn by geography and gender
- Age-based churn trends
- Tenure comparison between exited and retained customers
- Top 10 exited customers

# 4. Retention Analysis
- Retention trends
- Retained customers by geography
- Retained customers by gender
- Retention by credit card status

# Key DAX Measures

- Total Customers
- Total Exited Customers
- Total Retained Customers
- Churn Rate (%)
- Retention Rate (%)
- Average Tenure (Exited/Retained)

# Data Model

The project uses a Star Schema consisting of:

- 1 Fact Table: Bank_Churn
- 6 Dimension Tables:
  - Customer
  - Geography
  - Gender
  - CreditCard
  - ExitCustomer
  - ActiveCustomer

# Tech Stack

- Power BI
- Power Query
- DAX
- Star Schema Data Modeling
- Data Visualization
- Customer Churn Analytics
