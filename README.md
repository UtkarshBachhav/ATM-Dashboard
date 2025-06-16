# 🏧 ATM Transaction Analytics Dashboard (Power BI)

This repository contains a Power BI dashboard project that visualizes and analyzes **ATM transaction data**, enabling insights into usage trends, failure rates, and location-wise performance.

---

## 📌 Project Overview

- Developed an **interactive Power BI dashboard** to monitor ATM metrics such as transaction volume, success/failure rates, and location activity.
- Utilized **Power Query** for efficient data cleaning and transformation from raw logs.
- Built **DAX measures** to calculate:
  - ✅ Total and successful transactions  
  - ❌ Failure count and rates  
  - 📅 Time-based trends (daily/monthly)  
  - 🌍 Region- and ATM-wise performance
- Enabled better decision-making for banking operations and machine deployment optimization.

---

## 📊 Key Features

- 📌 **KPI Cards** for total transactions, failure %, average amount, etc.
- 📈 **Line & Bar Charts** showing temporal trends.
- 🌐 **Geo-location (if included)** to visualize ATM spread and performance.
- 🔍 **Slicers & Filters**: By ATM ID, date, city, status.
- 🚨 **Failure Diagnosis View**: Identify frequent failure causes or faulty machines.

---

## 🛠️ Tools & Technologies

```text
- Power BI Desktop
- Power Query (M Language)
- DAX (Data Analysis Expressions)
- Excel / CSV (ATM logs as data source)
