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
- **Source:** H₂ Fuel Station internal transaction
  records
- **Period:** January – December 2025
- **Size:** 31,896 transaction records
- **Structure:** 12 separate monthly Excel sheets
  consolidated into one dataset

![Raw monthly sheets before consolidation — attach your image here](images/fuel_raw_data.png)

---

## Dataset Overview
---

| Dimension | Detail |
|-----------|--------|
| Total Records | 31,896 |
| Columns | 16 |
| Period | January – December 2025 |
| Fuel Types | PMS, AGO, DPK |
| Customer Segments | Motorcycles, Cars, Buses, Trucks, Generators |
| Pumps | 6 (Pump 1 – Pump 6) |

**Key Variables:**
Transaction ID · Fuel Type · Pump Number ·
Sales Attendant · Asset Type · Litres Sold ·
Price Per Litre · Total Revenue · Payment Method ·
Transaction Time

---

## Tools Used
---
- **Microsoft Excel:** Primary tool for analysis
  and dashboard development
- **Power Query:** Used to append all 12 monthly
  sheets into one consolidated dataset, standardise
  data types, check for duplicates and clean the
  data — cutting manual processing time
  significantly
- **Excel Dashboard:** All KPI cards, charts and
  visualisations built directly in Excel
- **Calculated Columns:** Created new columns in
  Excel to support revenue analysis and
  segmentation

![Power Query consolidation — attach your image here](images/fuel_power_query.png)

---

## Data Cleaning & Preparation
---
The dataset came as 12 separate monthly Excel
sheets. The following steps were taken to prepare
it for full-year analysis.

**Step 1 — Appended all 12 monthly sheets**

Used Power Query in Excel to append all 12 monthly
files into one single consolidated dataset of
31,896 records — enabling full-year analysis
without manual copy-pasting.

![12 sheets appended into one dataset](images/fuel_append.png)

---

**Step 2 — Standardised data types**

Standardised column data types across all 12
sheets to ensure consistent formatting — dates,
numbers and text fields were aligned before
analysis began.

![Standardised data types in Power Query](images/fuel_standardised.png)

---

**Step 3 — Checked for duplicates**

Ran a full duplicate check across all 31,896
records. No duplicate records were found — the
dataset was clean.

![Duplicate check — no duplicates found](images/fuel_duplicates.png)

---

**Step 4 — Created calculated columns**

Created new columns to support revenue and
performance analysis including total revenue
calculations, profit margin fields and time-based
columns for hourly and monthly trend analysis.

![Calculated columns created in Excel](images/fuel_calculated_columns.png)

---

## Skills Demonstrated
---
- Multi-file Data Consolidation using Power Query
- Data Cleaning and Standardisation
- Duplicate Detection and Validation
- Calculated Column Creation
- Revenue Segmentation Analysis
- Customer Segment Performance Analysis
- Pump and Attendant Performance Evaluation
- Seasonal and Time-Based Trend Analysis
- Interactive Dashboard Design
- Data Storytelling and Business Recommendation
  Writing

---

## KPI Overview
---

| Metric | Value |
|--------|-------|
| Total Transaction Records | 31,896 |
| Period Covered | Jan – Dec 2025 |
| Top Revenue Fuel Type | PMS — 59.04% of revenue |
| Second Fuel Type | AGO — 37.46% of revenue |
| DPK Contribution | 3.50% of revenue |
| Top Customer Segment | Trucks — 56.98% of revenue |
| Lowest Performing Pump | Pump 4 |
| Peak Sales Month | December |
| Peak Sales Window | 3–5 PM daily |
| Gross Profit Margin | 3.68% |

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
