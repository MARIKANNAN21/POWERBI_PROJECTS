# Telecom Customer Churn Analysis Dashboard

## Project Overview
This project analyzes a telecom company's customer dataset to understand **churn patterns, service usage, revenue, and risk factors**. The goal is to provide actionable insights that help improve **customer retention, revenue optimization, and service strategies**.

The analysis is implemented in **Power BI** and includes interactive dashboards to explore key metrics and trends.

---

## Dataset
The dataset includes:

- **Customer Info:** `customerID`, `gender`, `SeniorCitizen`, `Partner`, `Dependents`  
- **Services:** `PhoneService`, `MultipleLines`, `InternetService`, `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`, `StreamingTV`, `StreamingMovies`  
- **Account Info:** `Contract`, `PaperlessBilling`, `PaymentMethod`, `tenure`, `MonthlyCharges`, `TotalCharges`  
- **Target Variable:** `Churn` (Yes/No)  

---

## Dashboard Pages

### 1. Home Page
- **Purpose:** Provides an **overview** and navigational entry point to the dashboard.  
- **Highlights:**  
  - High-level **questions** guiding the analysis, e.g.:  
    - Who are our high-risk customers?  
    - Which services drive churn?  
    - What is the financial impact of churn?  
  - Summary KPIs: Total Customers, Total Churned, Average Tenure, Total Revenue  

---

### 2. Subscriber Base Overview
- **Purpose:** Analyze **customer demographics and tenure**.  
- **KPIs & Highlights:**  
  - Customer distribution by **gender, senior citizen, partner/dependents**  
  - **Tenure distribution**  
  - **Churn rate by demographic segments**  
- **Outcome:** Identify **high-risk customer segments** and retention patterns.  

---

### 3. Service Overview
- **Purpose:** Evaluate **service adoption and its impact on churn**.  
- **KPIs & Highlights:**  
  - Service usage (Phone, Internet, Streaming, Tech Support)  
  - Churn rate by **individual services**  
  - Service combinations and multi-service adoption trends  
- **Outcome:** Identify **services correlated with higher churn** and opportunities for upselling or bundling.  

---

### 4. Financial Overview
- **Purpose:** Analyze **revenue patterns and financial impact of churn**.  
- **KPIs & Highlights:**  
  - Monthly Charges vs Churn  
  - Total Revenue lost due to churn  
  - Revenue contribution by customer segments and contracts  
- **Outcome:** Understand **financial loss due to churn** and prioritize **high-value customer retention**.  

---

### 5. Risk Overview
- **Purpose:** Assess **churn risk and critical factors**.  
- **KPIs & Highlights:**  
  - Churn rate by **contract type, payment method, and tenure**  
  - High-risk customer segments  
  - Predictive insights on potential churn (if integrated with ML)  
- **Outcome:** Identify **customers most likely to churn** and recommend **preventive actions**.  

---

## Tools & Technologies
- **Power BI:** Interactive dashboards and KPI visualization  
- **DAX:** Advanced measures for churn, revenue, and tenure  
- **Excel / CSV:** Data cleaning and preparation  

---

## Insights & Key Findings
- High churn is concentrated among **month-to-month contract customers** and **Electronic Check** payment users.  
- Customers with **long-term contracts and multiple services** have higher retention.  
- Service usage patterns suggest **opportunities for bundling or upselling** to reduce churn.  
- Financial analysis highlights **high-revenue at-risk segments**, guiding retention prioritization.  

---

## How to Use
1. Clone the repository:  
```bash
git clone https://github.com/yourusername/TelecomChurnAnalysis.git
