# 📊 Business Analytics Project

This project analyzes user behavior, purchase activity, and retention lifecycle using real transaction-level event data.  
Through cohort analysis, funnel evaluation, and retention measurement, this project provides critical insights into how users move through the platform and where business performance can be optimized.

---

## 🔥 Project Objectives

- Understand how users progress through the conversion funnel  
- Analyze customer retention and purchasing cohorts over time  
- Identify revenue opportunities through behavior patterns  
- Quantify first-purchase behavior and returning customer impact  

---

## 🛠 Tools & Technologies Used

| Tool | Purpose |
|---|---|
| **Excel / Google Sheets** | Data cleaning, formulas, aggregation |
| **Pivot Tables & Charts** | Cohort and retention visualization |
| **Analytical Frameworks** | Conversion funnel, cohort aging, retention tracking |

---

## 📁 Dataset Overview

The dataset consists of key behavioral logs and purchase events:

| Sheet Name | Description |
|---|---|
| `raw_user_activity` | Full event log w/ timestamps, prices & user_id |
| `purchase_activity` | Filtered purchase-only activity |
| `first_purchase` | First-transaction extraction per user |
| `retention_rates` | Monthly + aging retention matrix |
| `cohort_analysis` | Cohort-level grouping by first purchase month |
| `conversion_funnel` | User event flow through view → cart → purchase |

---

## 🔍 Key Analytics Performed

### 1️⃣ Conversion Funnel Analysis  
From the *conversion_funnel* sheet:

| Step | Users | Conversion to Next Step |
|---|---|
| **View** → Cart | 10,453 users → 29.04% continued |
| **Cart** → Purchase | 3,036 users → 35.6% continued |
| Final Purchase | 1,081 transactions |

**Insight:**  
Large majority drop occurs between **product view and checkout initiation**, suggesting opportunity for UX optimization or remarketing.

---

### 2️⃣ Cohort & Retention Analysis  
Cohorts grouped by **first purchase month**, then tracked as they age:

- Example cohorts:
  - **2020-09:** 32 users → dropped to 4 by month 1
  - **2020-10:** 187 users → fell gradually over 3+ months
  - **2020-11 & 2020-12:** continued decline with similar decay curve

**Insight:**  
Retention decreases sharply after month 1 — recurring engagement strategies may be needed.

---

### 3️⃣ First Purchase Behavior
`first_purchase` sheet identifies how quickly new customers convert:

- Most first-time users convert within the **first month**
- Delayed purchasing behavior is less common — meaning activation matters early

---

### 4️⃣ Revenue & Purchase Activity

`purchase_activity` shows:

- Full purchase event logs with price data
- Categories such as **computers**, **stationery**, **consumer electronics**
- Ability to track **AOV**, **LTV**, and **repeat purchase segments**

---

## 🚀 Business Takeaways

| Finding | Opportunity |
|---|---|
| High funnel drop-off early | Improve product page clarity / offer incentives |
| Retention declines after Month 1 | Build stronger post-purchase engagement |
| Early purchase conversion strong | Lean into onboarding + first-purchase triggers |


---

## 📂 How to Access the Project

1. Download `.xlsx` file  
2. Open sheets in Excel or Google Sheets  
3. Review insights on the **Executive Summary** page  
4. Explore deeper analysis through cohort, retention & funnel tabs

---

### 💼 Created by: **Marlon Romero**  
**Business & Data Analytics | Process + Insight-Driven Decision Making**

