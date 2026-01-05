# Power BI Sales & Customer Churn Dashboard

## Overview
This project analyzes business sales performance and customer churn using a star-schema data warehouse and Power BI.

The dashboard provides:
- Sales trends over time
- Category and subcategory performance
- Customer segmentation
- Churn analysis using recency-based logic
- KPI monitoring for business decision-making

## Data Model
- Fact table: Sales transactions
- Dimension tables: Customers, Products, Date
- Relationships follow star schema best practices

## Key KPIs
- Total Sales  
- Total Orders  
- Total Customers  
- Average Order Value (AOV)  
- Sales per Customer  
- Churned Customers  
- Churn Rate (%)  
- Active vs Churned Customers  

## Churn Logic
Customers are flagged as churned if no purchase is made in the last 6 months.
This logic is implemented using DAX for business transparency.

## Tools Used
- Power BI
- SQL Server
- DAX
- Star Schema Modeling

## Future Enhancements
- Predictive churn modeling using Machine Learning
- Sales forecasting
- Advanced customer behavior analysis

