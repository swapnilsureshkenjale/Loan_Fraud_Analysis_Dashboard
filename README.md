# Home_Analysis_Dashboard
An interactive Business Intelligence dashboard designed to analyze banking transactions, customer profiles, loan distributions, and account balances. This project translates raw banking operational data into actionable financial metrics and performance trends.
---

## 📊 Dashboard Previews

### 1. Account Balance Statistics
Deep-dive statistical summary highlighting overall balances, variance, and breakdown of account categories.
<img width="940" height="652" alt="image" src="https://github.com/user-attachments/assets/289b0b80-0731-46a3-bd21-1daad486e23c" />

### 2. Loan & Customer KPI Cards
A high-level view summarizing major loan KPIs, borrower volume, and demographic income averages.
<img width="1166" height="650" alt="image" src="https://github.com/user-attachments/assets/b286174a-0307-4188-876a-9a6d9fad42de" />

### 3. Transaction & Account ID Analysis
The core transaction workspace tracks changes in volumes, values, and transaction categories over time.
<img width="643" height="589" alt="image" src="https://github.com/user-attachments/assets/91cc07a3-5df0-4812-b309-bd586c87aa8c" />

---

## 📈 Key Insights & Features

### **Transaction Dynamics**
* **Granular Time-Series Tracking:** Monitors the "Sum of Amount" across specific historical IDs with interactive tooltips showing category performance breakdown (e.g., Transaction Type IDs `1`, `2`, `3`, and `4`).
* **Macro Trends (2020–2026):** Visualizes a sharp macroeconomic shift in transaction volumes and values starting from late 2023 through 2026.
* **Composition Breakdown:** An integrated pie chart highlights that **Transaction Type 1 (30.39%)** and **Transaction Type 3 (30%)** capture the majority of the transactional share.

### **Loan Portfolio Summary**
* **Customer Base:** Supports **1K Total Customers** spread across **50 active branches**.
* **Loan Distribution:** A total of **321 loans** have been issued, amounting to a **Total Loan Volume of 16.56M**, with an **Average Loan size of 51.59K**.
* **Financial Health:** Benchmarks these metrics against a customer base carrying an **Average Income of 48.96K**.

### **Account Balance Deep Dive**
* **Aggregate Volumetrics:** Tracks a massive total portfolio pool with a **Sum of Balance sitting at 79.21M** across **1,618 distinct Accounts**.
* **Statistical Distribution Metrics:**
  * **Average Balance:** 48.96K
  * **Median Balance:** 48.80K
  * **Max/Min Range:** Ranging from a maximum of 99.83K down to overdrawn accounts at -486.68.
  * **Spread Analysis:** Incorporates Standard Deviation (29.14K) and Variance (849.35M) calculations to evaluate risk and balance dispersion across Account Types (1 through 5).

---

## 🛠️ Technology Stack
* **BI Tool:** Power BI / Tableau *(Update based on your exact tool choice)*
* **Data Source:** Relational Banking Database (SQL) / CSV extracts
* **Data Modeling:** Star Schema / Snowflake Schema mapping Transactions, Accounts, and Loans.

---
