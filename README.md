# eCommerce-Analysis
### UK eCommerce Profitability and Customer Experience Dashboard

## Project Overview

This project is an end-to-end Power BI analytics solution built around a UK-based eCommerce retailer headquartered in Edinburgh.

The aim of the project was to move beyond simple reporting and build a business-focused dashboard that helps answer key commercial and operational questions around:

- profitability
- customer behaviour
- returns
- delivery performance
- marketing effectiveness
- regional performance across the UK

The project was approached from both a **data engineering** and **business intelligence** perspective, with a strong focus on building a clean, scalable reporting model before developing the visual layer.

---

## Business Problem

The retailer is growing across the UK, but profitability and customer experience may be under pressure due to:

- high return rates
- late deliveries
- discount-heavy sales
- uneven performance across customer segments, channels, and campaigns

The goal of this project was to identify where value is being created, where profit is being lost, and which business areas need attention first.

---

## Project Objectives

The dashboard was designed to help answer questions such as:

### Profitability
- Which product categories and subcategories drive the strongest gross profit?
- Which customer segments are most profitable?
- Are promotions improving profit, or only increasing discounted sales volume?

### Returns and Delivery
- What is the return rate by category, city, and sales channel?
- Which warehouses and shipping services are associated with higher late delivery rates?
- Is late delivery linked to higher return rates?

### Customer and Marketing
- Which marketing channels drive profitable growth?
- Which campaigns generate profitable orders rather than just volume?
- Which regions and customer groups create the most value?

---

## Tools Used

- **Power BI**
- **Power Query**
- **DAX**
- **Star schema data modelling**
- **Synthetic eCommerce dataset**

---

## Data Engineering and Modelling Approach

A key part of the project was treating the dashboard as a structured analytics solution rather than just a visual report.

### Data preparation included:
- cleaning and validating raw transaction data
- converting and standardising data types
- creating derived analytical columns
- validating financial and operational logic
- preparing a reporting-ready fact table

### Data model structure:
- **FactOrders**
- **DimCustomer**
- **DimProduct**
- **DimDate**
- **DimWarehouse**
- **DimCampaign**
- **DimChannel** *(optional / supporting dimension)*

This modelling approach allowed the report to scale more cleanly and supported reusable KPI logic across pages.

---

## KPI Design

The executive KPI layer focused on the measures that matter most to leadership:

- **Total Orders**
- **Net Sales**
- **Gross Profit**
- **Gross Margin %**
- **Return Rate**
- **Late Delivery Rate**

These KPIs were built to balance:
- business clarity
- technical consistency
- strong visual communication
- executive usability

---

## Dashboard Pages

### 1. Executive Overview
Provides a high-level summary of:
- total sales and profit
- margin performance
- return rate
- late delivery rate
- overall business health

### 2. Returns & Delivery Performance
Focused on identifying:
- return-heavy categories
- delivery issues by warehouse and shipping service
- operational hotspots
- profit impact of returns

### 3. Customers & Marketing Profitability
Focused on:
- customer segment value
- channel profitability
- campaign efficiency
- sustainable commercial growth

### 4. Detail Analysis / Drill-Through
Built for deeper investigation into:
- cities
- categories
- campaigns
- warehouses
- customer segments
- transaction-level evidence

---

## Key Features

- Clean star-schema modelling
- Business-ready KPI design
- Power Query transformation workflow
- Reusable DAX measures
- Interactive filters and drill-through analysis
- Executive-focused dashboard storytelling

---

## What This Project Demonstrates

This project reflects skills across:

### Data Engineering
- data cleaning
- transformation logic
- modelling design
- semantic structure for reporting

### Analytics and BI
- business problem framing
- KPI development
- DAX measure creation
- dashboard layout and storytelling

### Decision Support
- linking operational performance to profit outcomes
- surfacing return and delivery risks
- showing which channels, products, and segments drive value

---

## Key Learning

One of the biggest takeaways from this project is that strong dashboards are not built only in the visual layer.

They are built through:

- clean data structure
- reliable business logic
- thoughtful modelling
- clear KPI design
- purposeful storytelling

This project reinforced the importance of combining **technical structure** with **business understanding** to create dashboards that are useful, not just visually polished.

---

## Future Improvements

Potential next steps for this project include:

- adding forecast or trend prediction features
- building customer segmentation models
- adding basket analysis or repeat purchase analysis
- introducing anomaly detection for return spikes
- expanding operational SLA analysis

---

## Author

**Collins**  
Power BI | Data Analytics | Business Intelligence | Data Modelling

---

## Tags

`Power BI` `DAX` `Power Query` `Data Analytics` `Business Intelligence` `Dashboard Design` `Data Modelling` `eCommerce Analytics`

