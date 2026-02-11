# 📊 Customer Churn Analysis & Prediction | SQL Server · Power BI · Machine Learning

## 📌 Project Overview
In today’s competitive business environment, customer retention is critical for sustainable growth.  
This project presents an **end-to-end Customer Churn Analysis and Prediction solution** built using **SQL Server, Power BI, and Machine Learning (Random Forest)**.

The project covers the **complete analytics lifecycle**:
- Data ingestion and ETL
- Exploratory data analysis
- Interactive Power BI dashboards
- Churn profiling and insights
- Predictive churn modeling using Machine Learning
- Visualization of predicted churners for proactive decision-making

Although the dataset is from a **telecom domain**, the methodology and insights are **industry-agnostic** and can be applied to **retail, finance, SaaS, healthcare, and subscription-based businesses**.

---

## 🎯 Project Objectives
- Build a **robust ETL pipeline** using SQL Server
- Analyze customer churn across:
  - Demographics
  - Geography
  - Account & payment information
  - Services used
- Identify **churner profiles** and key churn drivers
- Create an **interactive Power BI dashboard**
- Predict **future churners** using a Machine Learning model
- Enable **data-driven marketing and retention strategies**

---

## 🧱 Tech Stack
| Layer | Tools |
|------|------|
| Database & ETL | Microsoft SQL Server, SSMS |
| Data Visualization | Power BI |
| Machine Learning | Python, Random Forest |
| ML Libraries | pandas, numpy, scikit-learn, seaborn, matplotlib |
| Environment | Anaconda, Jupyter Notebook |

---
## 🎯 Business Problem Solved

Customer churn directly affects revenue, profitability, and long-term growth.  
The telecom company lacked:

- A centralized analytical view of churn drivers  
- Clear identification of high-risk customer segments  
- Visibility into revenue impact due to churn  
- A predictive system to proactively prevent customer attrition  

This project addresses those challenges by building:

- A structured SQL-based ETL pipeline  
- An interactive Power BI dashboard for churn analysis  
- A Machine Learning model to predict future churners  
- A data-driven decision support framework for retention strategies  

The solution converts raw customer data into actionable business intelligence.

---

## 📊 Key Business Insights from Dashboard

### 1️⃣ Contract Type Drives Churn
- Month-to-Month contracts show significantly higher churn rates.
- 1-Year and 2-Year contracts demonstrate stronger retention.

**Business Recommendation:**  
Incentivize long-term contract adoption through discounts and loyalty benefits.

---

### 2️⃣ Payment Method Risk Patterns
- Customers using Electronic Check exhibit higher churn behavior.
- Auto-payment methods (Bank Transfer / Credit Card) correlate with lower churn.

**Business Recommendation:**  
Promote auto-payment enrollment campaigns to reduce churn risk.

---

### 3️⃣ Early Tenure Vulnerability
- Customers with tenure < 6 months show the highest churn probability.
- Churn stabilizes after 24 months.

**Business Recommendation:**  
Strengthen onboarding experience and early engagement programs.

---

### 4️⃣ Service Adoption Impact
Customers without value-added services such as:
- Online Security  
- Tech Support  
- Device Protection  

show higher churn tendencies.

**Business Recommendation:**  
Bundle additional services into personalized retention offers.

---

### 5️⃣ Geographic Churn Hotspots
- Certain states demonstrate elevated churn rates.
- Indicates potential regional competition or service quality issues.

**Business Recommendation:**  
Deploy targeted regional retention and operational improvement strategies.

---

### 6️⃣ Revenue Impact Analysis
- Churners contribute a measurable portion of total revenue.
- High-revenue churners represent priority retention opportunities.

**Business Recommendation:**  
Develop a “High Revenue At-Risk” customer intervention program.

---

## 📂 Project Architecture

1. **CSV Data**
   - Raw customer churn dataset imported into SQL Server.

2. **SQL Server (Staging → Production)**
   - Data loaded into staging table.
   - Data cleaning & null handling performed.
   - Production table created.
   - Analytical views (`vw_ChurnData`, `vw_JoinData`) generated.

3. **Power BI (Analysis Dashboard)**
   - Data transformation and modeling.
   - DAX measures created (Total Customers, Churn Rate, etc.).
   - Interactive dashboard built for churn analysis.

4. **Excel Export (For Machine Learning)**
   - SQL Views exported into Excel file.
   - Prepared dataset for ML training.

5. **Python (Random Forest Model)**
   - Data preprocessing (Label Encoding).
   - Train-test split.
   - Random Forest model training.
   - Model evaluation & feature importance analysis.

6. **Predicted Churners**
   - Predictions generated for new joiners.
   - High-risk customers identified.
   - Results exported as CSV.

7. **Power BI (Prediction Dashboard)**
   - Predicted churners visualized.
   - Demographic, account, and geographic risk insights displayed.
   - Enables targeted retention campaigns.





