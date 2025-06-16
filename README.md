# Mortage-Trading-Analysis
# 🏦 Mortgage Trading Analysis – Power BI Project

This Power BI project provides a comprehensive analysis of mortgage trading activities through five interactive dashboards. It aims to deliver insights into trade status, loan balances, pricing benchmarks, execution performance, and profitability, empowering data-driven decisions for mortgage-backed securities.

---

## 📊 Project Overview

The purpose of this analysis is to:
- Monitor the status of mortgage loan files throughout the trade process.
- Evaluate pricing and benchmark performance using key financial metrics.
- Analyze trade execution across counterparties.
- Understand profitability drivers with the help of AI-powered visuals.

---

## 📁 Dashboards Summary

### 1️⃣ **Report Overview Dashboard**
- **Purpose:** Evaluate trade readiness and audit status of mortgage loan files.
- **Key Features:**
  - **Custom Measure:** Trade Status calculated from loan status and audit timestamps.
  - **KPIs:** Debt-to-Income Ratio and Loan-to-Value Ratio.
  - **Table Visual:** Loan ID-wise trade status and audit progression.
  - **Pie Chart:** Distribution of loans by trade status (Ready to Trade, In Audit, etc.).

---

### 2️⃣ **Loan Balances Dashboard**
- **Purpose:** Track scheduled principal payments and upcoming obligations.
- **Key Features:**
  - **Calculated Measure:** Scheduled Principal Amount derived using current balance, next payment dates, and amortization.
  - **Table Visual:** Displays loan_id, scheduled amounts, and relevant dates.
  - **Slicer:** Filters loan balances by trade status.

---

### 3️⃣ **Trade Analysis Dashboard**
- **Purpose:** Analyze loan prices, benchmark comparisons, and trading performance.
- **Key Features:**
  - **KPI Cards:** Average Price and Weighted Average Price (weighted by principal).
  - **Pie Chart:** Benchmark Test showing "True/False" for loans priced above UMBS benchmarks.
  - **Table Visual:** Trade Amount and Trade Premium per loan, aiding in gain/loss analysis.

---

### 4️⃣ **Trade Execution Dashboard**
- **Purpose:** Evaluate counterparty performance in terms of executed trades.
- **Key Features:**
  - **Stacked Bar Chart:** Sum of Trade Premium by counterparty.
  - **Clustered Column Chart:** Sum of Trade Amount by counterparty.
  - **Table Visual:** Full trade metrics by loan_id, filterable by counterparty.

---

### 5️⃣ **Profit Analysis & Key Influencers**
- **Purpose:** Analyze profitability and understand key pricing drivers.
- **Key Features:**
  - **Measures:** Loan Gross Profit, Profit Margin, Total Revenue, Target Profit.
  - **Table Visual:** Loan-level profitability with principal balance and target margin.
  - **Key Influencers Visual (AI-Powered):**
    - Performs regression-style analysis using:
      - Sum of UMBS Price
      - Sum of Median FICO Score (creditworthiness)
      - Debt-to-Income (DTI) Ratio
      - Loan-to-Value (LTV) Ratio
    - Highlights statistically significant factors affecting loan price.
    - Offers intuitive insights without manual modeling.

---

## ⚙️ Tools & Technologies
- **Power BI Desktop**
- **DAX Measures**
- **AI Visuals (Key Influencers)**
- **Interactive Visualizations (Slicers, Charts, Tables)**

---

## 📈 Key Outcomes
- Identified audit and trade-readiness gaps in loan files.
- Compared actual loan prices with UMBS benchmarks.
- Analyzed profitability by loan, counterparty, and pricing factors.
- Leveraged Power BI's AI capabilities for explainable, data-driven insights.
