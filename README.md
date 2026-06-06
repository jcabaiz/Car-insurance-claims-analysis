# Car Insurance Claim Analysis

An end-to-end data analysis project investigating driver demographics, policy types, and premium configurations to identify key risk factors and optimize portfolio profitability.

---

## 📌 Problem Statement
Our insurance portfolio is currently experiencing an overall claim rate of **21.43%** across its customer base. When a claim event occurs, the financial impact is substantial, resulting in an average payout of **$34,622**. 

High-frequency or high-cost claim events within specific coverage tiers and demographic groups threaten to compress corporate profit margins. The primary objective of this project is to analyze asset concentration, policy types, and driver demographics to uncover the core drivers of these claims, allowing stakeholders to precisely calibrate premium pricing and implement strategic risk-mitigation plans.

---

## 📊 Data
The analysis evaluates a dataset representing **2,002 unique policies** (total customers). The operational baseline metrics calculated from this dataset include:

* **Total Policies:** 2,002
* **Portfolio Claim Rate:** 21.43%
* **Average Monthly Premium:** $1,859
* **Average Claim Amount:** $34,622 (among claimants only)
---

## 🛠️ Methodology and Tools
To ensure data integrity and create an impactful presentation for stakeholders, a streamlined two-step data pipeline was utilized:

1.  **Data Cleaning & Preprocessing (Microsoft Excel):**
    * Inspected the raw dataset for missing values, structural inconsistencies, and anomalies.
    * **Handling Missing Data:** Applied **median imputation** to fill missing numerical values across variables, protecting the dataset from rows being aggressively dropped while preserving the overall distribution shape.
2.  **Data Visualization & Modeling (Power BI):**
    * Imported the clean dataset into Power BI to build an interactive analytical dashboard.
    * Utilized DAX to construct core KPIs (Total Policies, Claim Rate, Average Premium, and Average Claim Amount).
    * Engineered responsive visual assets including donut charts, horizontal bar charts, and age-distribution area graphs to segment risk profiles cleanly.

---

## 🔍 Insights
* **The Coverage Disparity:** Standard coverage policyholders generated the highest absolute number of claim events (**143 claims**), outperforming Basic (**131 claims**) and Comprehensive (**124 claims**). This points to an unfavorable risk-selection bias where riskier drivers heavily prefer mid-tier coverage.

  <img width="476" height="232" alt="image" src="https://github.com/user-attachments/assets/13c3d1f9-af09-4762-978e-04c6379f6ae8" />

* **Primary Risk Driver:** Vehicle **Collisions** are the undisputed driver of financial liability, accounting for **49.71%** (nearly half) of all claim reasons. This drastically outpaces Theft (20.52%) and Weather (12.83%).
  <img width="477" height="233" alt="image" src="https://github.com/user-attachments/assets/a4d6274d-3e6d-4b20-b169-416c2e68920a" />

* **Premium Volatility by Age:** Premium structures show severe volatility across age brackets. Average premiums spike near **$2,500** for young drivers (early 20s), flatten out to a steady valley ($1,500 - $1,800) during middle-age, and climb back up toward **$2,000+** for drivers over 60.
  
  <img width="853" height="248" alt="image" src="https://github.com/user-attachments/assets/0cc6735d-94fe-4d5e-8400-fc20879c87f9" />

---

## 💡 Recommendations
1.  **Introduce Telematics & Safety Incentives:** Because collisions make up **49.71%** of our claims, introducing small, opt-in premium discounts for safe driving metrics or claim-free milestone years will directly incentivize lower accident rates.
2.  **Audit the Standard Coverage Underwriting:** Standard coverage is seeing an absolute peak of **143 claims**. We should review our underwriting guidelines and pricing model for this specific tier to ensure its premium yields adequately offset the high frequency of risk.
3.  **Smooth Age-Bracket Premium Curves:** Address the age premium volatility curve. Standardizing the mathematical models for extreme age groups (under 25 and over 60) will create more predictable revenue pipelines and improve pricing competitiveness among safe senior drivers.

