# Kraken-Koffee-Infographic

![Kraken Koffee Dashboard](KrakenKoffeeDashboard.jpg)

## Introduction
In this project, I worked as a **Business Intelligence Developer** to analyze sales and transaction data for **Kraken Koffee**, a fictional coffee chain expanding into Florida. The objective was to build an **interactive Power BI infographic** that provides insights into key areas such as **top products, peak sales periods, store performance, and future sales projections**.

---

## Skills and Concepts Demonstrated
- **Data Cleaning and Transformation (Power Query)**
- **Data Modelling (Star Schema)**
- **DAX Calculations (KPIs, Rankings, Forecasting)**
- **Data Visualization and Storytelling**
- **Business Intelligence Reporting**

---

## Tools Used
- Power BI  
- Power Query  
- DAX  
- Data Visualization & Storytelling

---

## Key Objectives
- Clean and transform raw sales data to prepare for analysis.
- Build a robust data model using a star schema.
- Develop core measures using DAX for key metrics like sales, average order size, and product ranking.
- Create compelling visualizations that tell a story for stakeholders.
- Forecast future sales based on historical performance.

---

## Process Summary
### Data Transformation
- Removed unnecessary columns and unchecked irrelevant data to reduce load time.
- Split data into fact and dimension tables (store, product, date).
- Added calculated columns (e.g., transaction value, hour of sale).
- Created a date table enriched with month names, day names, and their abbreviations.

### Data Modelling
- Implemented a **star schema** with one fact table (transactions) and three dimension tables (store, product, date).
- Established **one-to-many** relationships across tables.

### DAX Measures
Created key performance measures, including:
- Total Transactions
- Total Sales
- Average Order Size
- Product Sales Rank
- Top Products & Stores
- Forecasted Sales

---

## Visualizations
The dashboard consists of 4 pages:

### 1. Summary Data (Hidden)
Core DAX measures calculated for use across visuals.

### 2. Summary Visuals
- Top 10 Products by Sales
- Total Sales by Product Category
- Sales Trends by Hour & Day
- Matrix & Hierarchical Visuals to explore product and location performance

### 3. Rough Forecast
- Full-Year Sales Forecast using average daily sales trends.
- Store-level forecast comparisons.

### 4. Forecast Visuals
- Monthly projected sales for each store.
- Store and day performance matrix.
- Product category rank visual.

---

## Key Insights
- **Best-Selling Product:** Davy Jones' Sustainably Grown Organic Hot Chocolate Lg
- **Peak Sales Hour:** 10 AM
- **Lowest Sales Period:** Before 7 AM and after 7 PM (only 3.6% of total sales)
- **Top Day:** Monday
- **Lowest Day:** Sunday
- **Rising Trend:** Significant sales growth seen from April to June

---

## Recommendations
- **Adjust Store Hours:** Align operating hours to match peak sales periods.
- **Product Strategy:** Focus on high-performing products (e.g., hot chocolate, dark chocolate blends).
- **Forecast-Based Planning:** Use projections to set monthly sales targets and plan campaigns.
- **Localized Marketing:** Customize offerings based on location-specific preferences.
- **Continuous Monitoring:** Update dashboards regularly to track performance.

---

## Final Note
This project demonstrates proficiency in **data transformation, data modeling, advanced DAX calculations, forecasting, and data storytelling** using Power BI, and showcases how data-driven decisions can improve operational efficiency and revenue optimization for retail businesses.
