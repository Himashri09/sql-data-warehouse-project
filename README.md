# End-to-End Sales & Customer Churn Analytics Platform

## Overview
This project demonstrates a complete business analytics workflow — from raw transactional data to executive-ready dashboards.

It combines:
- A **star-schema SQL data warehouse**
- **Advanced SQL analytics**
- **Interactive Power BI dashboards** for sales and customer churn analysis

The goal is to showcase how data can be modeled, analyzed, and visualized to support **data-driven business decisions**.

## Architecture
**Data Flow**
Raw Sales Data
↓
SQL Server Data Warehouse (Star Schema)
↓
SQL Analysis & Aggregations
↓
Power BI Dashboards

## Data Warehouse Design
- **Fact Table**
  - Sales transactions

- **Dimension Tables**
  - Customers
  - Products
  - Date

- Designed using **star schema best practices**
- Surrogate keys used for efficient joins
- Optimized for analytical queries


## Power BI Dashboards
Two main dashboards were built:

### 📊 Sales Overview Dashboard
- Sales trends by year
- Category & subcategory performance
- Top products by revenue
- Geographic sales distribution
- Customer segmentation insights

### 🔄 Customer Churn Dashboard
- Active vs Churned customer split
- Churn rate over time
- Churn by category and country
- High-risk customer segments

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
Customers are classified as **churned** if they have not made a purchase in the **last 6 months**.

- Logic implemented using **DAX**
- Simple, transparent, and business-friendly
- Suitable for executive reporting and decision-making


## Tools & Technologies
- **SQL Server** – Data warehouse & analysis
- **SQL** – Data modeling and analytics
- **Power BI** – Data visualization & dashboards
- **DAX** – Business metrics & churn logic
- **Git & GitHub** – Version control & documentation

## Project Highlights
- End-to-end analytics lifecycle
- Industry-standard star schema design
- Business-oriented KPI tracking
- Clean and intuitive dashboard design
- Resume-ready analytics portfolio project

## Future Enhancements
- Predictive churn modeling using Machine Learning
- Sales forecasting
- Cohort-based customer analysis
- Incremental data refresh pipelines

## Dashboard Preview
> Screenshots of dashboards are included.

## Author
**Himashri Masthi**  
Data Analytics | SQL | Power BI | Business Intelligence
