# 📉 Retail Operations Audit: Revenue Leakage Detection

**Auditor:** KD Mehta
**Tools:** R (Tidyverse), Python, GenAI

### 🚀 Executive Summary
This project simulated an **Internal Audit** on retail sales data to identify the root cause of negative profitability.
* **Finding:** Transactions with discounts >20% account for 80% of losses.
* **Risk:** No automated approval lock exists for high discounts.
* **Action:** Built an automated script to flag these "High Risk" transactions instantly.

### 📊 Key Risk Indicator (KRI) Visualization
*(This chart identifies the exact "bleeding point" where profit turns negative)*

![Audit Chart](Revenue_Leakage_Chart.png)

### 📂 Project Files
* **https://rpubs.com/KDMehta95/Revenue_Audit**
* **Code:** `audit_script.Rmd` (R Markdown) & `Revenue_Leakage_Audit_detecting_'Discount_Abuse'_in_Sales_Data.ipynb` (Python Logic)
