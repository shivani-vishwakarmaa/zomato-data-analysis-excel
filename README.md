# Vrinda Store Data Analysis (Excel Dashboard)

## Overview
This project analyzes sales data for Vrinda Store using Microsoft Excel. The goal is to identify key trends in customer behavior, sales performance, and operational efficiency, and to provide actionable business recommendations.

## Objectives
- Analyze sales trends across time, regions, and customer segments
- Identify high-performing products, states, and sales channels
- Evaluate order fulfillment performance
- Understand customer demographics and purchasing behavior

![Vrinda Store Dashboard](https://raw.githubusercontent.com/shivani-vishwakarmaa/vrinda_store-data-analysis-excel/main/dashboard.png)



## Dataset
The dataset contains transactional sales data with the following key fields:
- Order ID, Customer ID
- Gender, Age, Age Group
- Order Date, Month
- Order Status
- Sales Channel (Amazon, Myntra, Flipkart, etc.)
- Product Category and SKU
- Quantity and Revenue (Amount)
- Shipping City and State

## Methodology
- Cleaned and standardized raw data (handled inconsistencies, created derived columns such as age group)
- Performed analysis using Pivot Tables
- Built an interactive dashboard using charts and slicers
- Structured the workbook into:
  - Dashboard
  - Cleaned Data
  - Pivot Tables
  - Summary and Recommendations

## Dashboard
The dashboard provides an interactive view of:
- Sales trends over time
- Customer segmentation by gender and age group
- Sales distribution across states
- Order status and fulfillment rates
- Channel-wise performance

Slicers are used to filter data dynamically by key dimensions such as category, gender, and region.

## Key Insights
- Sales peaked in March, indicating strong seasonal demand, likely driven by promotions or end-of-season buying behavior
- Female customers contributed the majority of purchases, making them the primary revenue-driving segment
- Order fulfillment rate is high (~92%), but ~8% delivery failures indicate a gap in logistics
- Top-performing states include Maharashtra, Karnataka, and Uttar Pradesh, contributing the largest share of total sales
- Middle-aged and senior women are the most active buyers, showing strong purchasing power
- Sales are highly dependent on marketplace channels such as Amazon, Myntra, and Flipkart

## Recommendations
- Target high-value segments (middle-aged and senior women) with personalized marketing and product recommendations
- Increase marketing efforts in top-performing states to maximize return on investment
- Run promotional campaigns before March to capitalize on seasonal demand peaks
- Improve logistics to reduce delivery failure rates, especially in high-demand regions
- Strengthen partnerships with major sales channels or optimize product listings for better visibility

## File Structure
- `vrinda_dashboard.xlsm` – Excel file containing dashboard, analysis, and VBA navigation
- `dataset.csv` – Source dataset
- `dashboard.png` – Dashboard preview image

## How to Use
- Download the Excel file
- Open in Microsoft Excel
- Enable macros if prompted (required for navigation features)
- Use slicers on the dashboard to explore the data interactively

## Limitations
- Analysis is based on available historical data only
- External factors such as market trends and competition are not included
- Assumes data accuracy after cleaning

## Future Improvements
- Integrate Power BI for advanced visualization
- Add forecasting for sales trends
- Include customer retention and cohort analysis
