# H₂ FUEL STATION — SALES & PERFORMANCE ANALYSIS (2025)
---

# Table of Contents
---
- [Analysis Overview](#analysis-overview)
- [Business Overview](#business-overview)
- [Objectives](#objectives)
- [Data Source](#data-source)
- [Dataset Overview](#dataset-overview)
- [Tools Used](#tools-used)
- [Data Cleaning & Preparation](#data-cleaning--preparation)
- [Skills Demonstrated](#skills-demonstrated)
- [KPI Overview](#kpi-overview)
- [Insights](#insights)
- [Recommendations](#recommendations)
- [Dashboard](#dashboard)
- [Conclusion](#conclusion)

---
## Analysis Overview

This project analyzes 31,896 fuel station transactions recorded throughout 2025 to identify revenue drivers, customer purchasing patterns, and operational performance. The dashboard was developed using Excel, Power Query, and Power Pivot to support data-driven business decisions.

---

## Problem Statement

Fuel stations generate thousands of transactions every day, making it challenging to understand which products, customer segments, and operations contribute most to revenue and profitability. This analysis addresses that challenge by uncovering key performance trends and operational opportunities.

---

## Objectives

- Analyze monthly and annual revenue performance.
- Identify the highest revenue-generating fuel products.
- Evaluate sales across customer segments.
- Determine peak sales hours and months.
- Assess pump and attendant performance.
- Compare weekday and weekend sales patterns.
- Evaluate overall profitability.
---

## Data Source

---

The dataset consists of **31,896 fuel station transactions** covering **January to December 2025**. The data was provided as **12 monthly Excel worksheets** and consolidated into a single dataset for analysis.

![Raw Dataset](images/raw_data.png)

---

## Tools Used

---

- **Microsoft Excel** – Data analysis and dashboard development.
- **Power Query** – Consolidated monthly worksheets and performed data transformation.
- **Power Pivot** – Created calculated measures for KPI reporting.
- **Pivot Tables & Charts** – Built interactive dashboard visualizations.

---

## Key Metrics Created

---

The following metrics were created to evaluate business performance:

- **Total Revenue**
- **Gross Profit**
- **Total Fuel Cost**
- **Profit Margin**
- **Average Daily Revenue**

![Key Metrics](images/key_metrics.png)

---

## Data Preparation

---

The dataset was prepared using Power Query by:

- Consolidating 12 monthly worksheets into a single dataset.
- Standardizing data types and formatting.
- Validating data quality and checking for duplicate records.
- Creating calculated columns to support time-based and profitability analysis.

![Power Query Transformation](images/power_query.png)

---
## Skills Demonstrated

---

- Data Transformation and Consolidation (Power Query)
- Data Cleaning and Validation
- KPI Development and Performance Analysis
- Revenue and Profitability Analysis
- Customer Segmentation Analysis
- Operational Performance Analysis
- Time Series and Trend Analysis
- Dashboard Design and Data Visualization
- Data Storytelling and Business Recommendations
```
---

## Insights
---

### Insight 1 — Trucks generate 56.98% of total revenue — the station's most critical customer

Despite serving five customer segments, trucks
dominate revenue so heavily that the station's
financial health depends on them. PMS accounts
for 59.04% of revenue and AGO — the primary truck
fuel — accounts for 37.46%. Together these two
fuels make up 96.5% of total revenue.

| Fuel Type | Revenue Share |
|-----------|--------------|
| PMS (Petrol) | 59.04% |
| AGO (Diesel) | 37.46% |
| DPK (Kerosene) | 3.50% |

![Revenue by customer segment — attach your image here](images/fuel1.png)

![Revenue by fuel type — attach your image here](images/fuel2.png)

**Key Takeaway:**
The station's product and service strategy is
essentially already decided by the data — trucks
and PMS are the core of the business. Everything
else is secondary.

---

### Insight 2 — Pump 4 is the lowest-revenue pump — and the cause is unknown

Pump 4 recorded the lowest revenue across all 6
pumps consistently throughout the year. In a
station where pumps should share similar traffic,
one that persistently underperforms signals a
problem — whether mechanical, operational or
customer-related.

![Revenue by pump number — attach your image here](images/fuel3.png)

**Key Takeaway:**
Inspect Pump 4 for mechanical or accuracy issues.
Compare transaction count vs revenue to diagnose
whether this is a volume problem or a per-transaction
value problem — the fix depends on the answer.

---

### Insight 3 — December and 3–5 PM are peak periods — but neither is being planned for

December recorded the highest monthly revenue
driven by festive travel and increased
transportation demand. Within each day, the
3–5 PM window is the peak transaction period —
aligning with closing-hour logistics and truck
route schedules. DPK also showed a seasonal spike
between March and May.

![Monthly revenue trend — attach your image here](images/fuel4.png)

![Revenue by hour of day — attach your image here](images/fuel5.png)

**Key Takeaway:**
Pre-stock additional fuel before December. Assign
maximum staffing during the 3–5 PM window every
day. Adjust DPK ordering to anticipate the
March–May demand uptick.

---

### Insight 4 — Gross profit margin is 3.68% — healthy but leaving no room for waste

A 3.68% gross margin is within the normal range
for retail fuel stations where commodity pricing
compresses margins. But at this level, small
operational inefficiencies — a low-performing pump,
overstocking the wrong fuel or under-staffing the
peak window — have a disproportionate impact on
profitability.

**Key Takeaway:**
Every pump, every attendant and every stock
decision either protects the margin or erodes it.
Expanding high-margin ancillary products — engine
oil, car accessories, convenience items — directly
improves the margin without needing to increase
fuel volume.

---

## Recommendations
---

**Maximise Truck Revenue**
- Dedicate faster refuelling lanes for trucks
  during peak hours
- Ensure AGO is always adequately stocked
- Introduce a loyalty programme for regular truck
  drivers to lock in repeat commercial volume

**Investigate Pump 4**
- Inspect for mechanical or accuracy issues
- Review attendant assignment patterns at that pump
- Compare transaction count vs revenue to isolate
  the root cause

**Plan for Peak Periods**
- Pre-stock for December demand surge
- Assign maximum staff coverage every day during
  3–5 PM
- Adjust DPK ordering for the March–May seasonal
  uptick

**Expand Revenue Streams**
- Add high-margin ancillary products — engine oil,
  car accessories and convenience store items
- These require minimal operational change but
  directly improve the 3.68% gross margin

**Monitor Attendant Performance**
- Review attendant sales distribution regularly
- Identify consistently low-performing assignments
  and investigate whether this is a training,
  scheduling or placement issue

---

## Dashboard
---
One interactive dashboard was built in Excel
covering all key performance areas — revenue by
fuel type, customer segment, pump, attendant,
peak hours, monthly trends and profit margin.

![Dashboard — H₂ Fuel Station Sales and Performance](images/fuel-dashboard.png)

---

## Conclusion
---
This analysis of 31,896 fuel station transactions
reveals that the station is performing at a normal
level — but normal is not the ceiling.

Trucks and PMS are carrying the entire business.
Pump 4 is quietly underperforming. December and
the 3–5 PM window are peak periods that are not
being actively planned for. And a 3.68% margin
means there is very little room for operational
waste.

The good news: every one of these findings is
fixable. The data has already identified where
the opportunities are — the next step is acting
on them.

Data fuels better decisions.

---

Thank you for reading!

Let's connect:

[LinkedIn](https://www.linkedin.com/in/peace-ada-95b341341)
[Portfolio](https://peace-ada.github.io/Data-Portfolio/)
[Email](mailto:peaceada100@gmail.com)
