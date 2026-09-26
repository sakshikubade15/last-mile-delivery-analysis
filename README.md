# Last-Mile Delivery Operations & Delay Analysis

## 📌 Project Overview

This project analyzes last-mile delivery operations using Microsoft Excel.

The objective is to understand delivery performance, identify delay patterns, compare operational performance across cities, delivery partners and shipping modes, and provide business-oriented insights.

## 📊 Dataset

The project uses a simulated dataset containing 10,000 delivery orders covering January 2026 to June 2026.

The dataset includes information such as:

- Order details
- Customer information
- City and state
- Product category
- Delivery partner
- Shipping mode
- Promised and actual delivery dates
- Delivery status
- Delay reason
- Delivery cost
- Distance
- Priority
- Customer rating
- Payment mode

## 🛠️ Tools & Excel Skills

- Microsoft Excel
- Data Cleaning
- Excel Tables
- IF / IFS
- COUNTIF / COUNTIFS
- SUM / AVERAGE
- AVERAGEIF / AVERAGEIFS
- MIN / MAX / MEDIAN
- STDEV.S
- Date Functions
- XLOOKUP
- VLOOKUP
- INDEX + MATCH
- Conditional Formatting
- PivotTables
- PivotCharts
- Slicers
- Dashboarding
- Business Analysis

## 🔄 Analysis Workflow

Raw Data
→ Data Cleaning
→ Calculated Columns
→ KPI Analysis
→ Segmentation
→ PivotTables
→ PivotCharts
→ Dashboard
→ Business Insights

## 📈 Key Metrics

| Metric | Result |
|---|---:|
| Total Orders | 10,000 |
| Delivered Orders | 9,614 |
| Late Orders | 1,580 |
| Failed Orders | 184 |
| Returned Orders | 202 |
| On-Time Delivery | 83.57% |

## 🔎 Key Findings

- Overall observed on-time delivery was 83.57%.
- City-level observed on-time rates ranged from 81.00% to 85.46%.
- Delivery partner on-time rates ranged from 82.93% to 83.92%.
- Weekend orders had an observed on-time rate of 82.05%, compared with 84.18% for weekdays.
- Among late orders with a recorded delay reason, Address Issue was the most frequently recorded reason.
- Warehouse Delay had the highest average delay among the recorded delay reasons.

## ⚠️ Data Quality Limitation

There were 1,580 late orders, but 1,377 did not contain a recorded delay reason.

Therefore, delay-reason analysis was performed only on the 203 late orders where a reason was available.

## 💡 Business Recommendations

- Improve the completeness of delay-reason tracking.
- Investigate city-level differences in delivery performance.
- Review warehouse processing and dispatch delays.
- Monitor weekend delivery operations.
- Track delivery performance regularly through an operational dashboard.

## 📁 Workbook Structure

The Excel workbook contains:

- `README` — Project information
- `01_Raw_Data` — Original dataset
- `02_Cleaned_Data` — Cleaned dataset and calculated columns
- `03_Calculations` — KPI and detailed analysis
- `04_Pivot_Analysis` — PivotTables and PivotCharts
- `05_Dashboard` — Interactive Excel dashboard
- `06_Insights` — Business findings and recommendations

## 📌 Note

This dataset is simulated for portfolio and learning purposes and does not represent the actual operations or data of a real company.