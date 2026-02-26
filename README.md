# Online Retail UK – Sales & Customer Analytics (Power BI)

This project demonstrates an end-to-end Business Intelligence workflow using transactional retail data from a UK-based e-commerce company (Dec 2010 – Dec 2011).

The objective is to transform raw transaction-level data into actionable business insights related to sales performance, customer segmentation, retention, and lifetime value.

This project highlights both technical implementation (Power BI & DAX) and business interpretation.

----

## Objectives
- Analyze sales performance and seasonality
- Identify high-value customers and revenue concentration
- Measure customer retention and churn behavior
- Perform cohort analysis to understand repeat purchasing patterns
- Estimate customer lifetime and long-term value impact

----

## Dataset Information
- Source: Public Online Retail dataset
- Period Covered: December 2010 – December 2011
- ~500,000 transaction records
- Key Fields:
  - InvoiceDate
  - CustomerID
  - Quantity
  - UnitPrice
  - Country
Note: 2010 data includes December only. Analysis is interpreted accordingly.

----

## Technical Implementation
- Data Preparation:
  - Removed canceled transactions
  - Standardized date format
  - Created dedicated Date Table
  - Built star-schema inspired data model
- Power BI & DAX Features Used:
  - Time Intelligence (YTD, Monthly comparison)
  - Customer Segmentation logic
  - Retention rate calculation
  - Cohort analysis matrix
  - Customer Lifetime calculation
  - Revenue contribution analysis

----

## Tools & Skills Used
- Power BI
- DAX (CALCULATE, Time Intelligence, Cohort Logic)
- Data Modeling (Star Schema)
- Customer Segmentation
- Retention & Churn Analysis

----

## Key Insights
- Total Sales: £991.7M
- Strong upward sales trend with significant Q4 spike
- Revenue highly concentrated in Top 10 products
- Small % of high-value customers contribute majority of revenue
- Average monthly retention ~37%
- Retention declines after first few months
- Customer lifetime directly correlates with revenue contribution

----

## Business Recommendations
1. Prioritize retention campaigns within first 3 months of acquisition
2. Focus CRM initiatives on high-value customer segment
3. Align inventory and marketing strategy with Q4 seasonality
4. Optimize product portfolio around top-performing items

----

## Skills Demonstrated
- Business Problem Framing
- KPI Definition & Dashboard Design
- Data Modeling (Star Schema)
- DAX (Cohort, Retention, Time Intelligence)
- Insight Storytelling
- Translating Data into Strategic Action

-----

## Dashboard Preview
