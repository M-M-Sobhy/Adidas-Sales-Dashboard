# Customer Churn Analysis Dashboard

An end-to-end data visualization project analyzing telecommunications churn to identify why customers leave and which segments are most at risk.

## 📊 Project Overview
This repository contains a comprehensive churn analysis dashboard. The goal is to provide actionable insights into customer behavior, competitor influence, and demographic trends to reduce the current churn rate.

![overview-churn](https://github.com/user-attachments/assets/d19db6c0-fbf2-49d3-bab2-78e0578b9b39)
![overview](https://github.com/user-attachments/assets/9602fffe-702e-46dc-8d7b-723aad255486)


### 📈 Key Performance Indicators (KPIs)
| Metric | Value |
| :--- | :--- |
| **Total Customers** | 6,687 |
| **Churned Customers** | 1,796 |
| **Churn Rate** | 26.86% |
| **Avg. Monthly Charge** | $31.03 |
| **ARPU (Avg. Revenue Per User)** | $1,084 |

---

## 🔍 Key Insights

### 1. Competitor Influence
The primary reason for churn is competitive pressure. 
* **Better Offers & Devices:** Combined, these account for **75%** of churn reasons.
* **Data & Speed:** 26% of customers left for better download speeds or higher data caps.

### 2. Demographic Vulnerability
* **Age Sensitivity:** Churn rates increase significantly in older populations, peaking at over **40%** for the 79-88 age bracket.
* **Segment Focus:** Senior citizens represent **44%** of the churned population, despite being a smaller portion of the total customer base.

### 3. Regional Performance
* High-churn states (filtered by International Plan) include **California (75%)** and **Indiana (66.67%)**.

---

## 🛠️ Technical Implementation
* **Tool:** Power BI / Excel
* **Data Modeling:** Star Schema with a central Fact table and Dimension tables for Geography, Demographics, and Churn Reasons.
* **Calculations:** * `Churn Rate % = DIVIDE([Churned Customers], [Total Customers])`
    * `ARPU = [Total Revenue] / [Total Customers]`

## 📂 Visuals Reference
The dashboard consists of two main views:
1. **Overview:** High-level KPIs and Churn Reasons.
2. **Customer Analysis:** Deep dive into Age, Consumption, and Demographics.

---

## 🚀 Future Recommendations
* **Retention Offers:** Create targeted promotions for the "Senior" demographic.
* **Hardware Upgrades:** Investigate "Competitor Devices" to see if a hardware refresh program is necessary.
* **Regional Strategy:** Conduct a localized marketing audit in California (CA) to address the 75% churn rate.
