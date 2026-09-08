# Coffee-Sales-Performance-Dashboard-Excel
Transforming raw coffee sales data into actionable business insights using Excel, Power Query, and an interactive dashboard.


## Overview
This project analyses coffee sales data using Microsoft Excel and Power Query to understand sales performance, product performance, and customer loyalty.

The project covers data preparation, transformation, analysis, and dashboard development using an interactive Excel dashboard.


## Project Objectives
* Analyse coffee sales performance
* Track revenue and sales trends
* Compare coffee type performance
* Analyse customer loyalty card usage
* Identify key sales patterns through an interactive dashboard

## Data Preparation
The dataset contains three related tables: Orders, Customers, and Products.

## Power Query
* Removed unused columns and cleared existing filters
* Imported all three tables into Power Query
* Renamed the queries for easier management
* Merged Orders + Customers using Customer ID
* Merged the main data with Products using Product ID
* Selected relevant product information: Coffee Type, Roast Type, Size, and Unit Price

## Value Standardisation
**Coffee Type**
- Rob → Robusta
- Ara → Arabica
- Exc → Excelsa
- Lib → Liberica

**Roast Type**
- D → Dark
- L → Light
- M → Medium

The Replace Values function in Power Query was used to standardise these categories.

## Revenue Calculation
Created a new Revenue column:
Revenue = Quantity × Unit Price
The calculation was created using Add Column → Standard → Multiply.
The final dataset was then loaded back into Excel for PivotTable analysis and dashboard development.

## 📊 Dashboard

The interactive dashboard provides an overview of sales performance, product performance, and customer loyalty.

### Key Metrics

- **Revenue:** $45,134.26
- **Quantity Sold:** 3,551
- **Customers:** 1,000

### Interactive Filters

**Year · Country · Coffee Type · Roast Type · Size**

## 💡 Key Business Insights

- **Excelsa** generated the highest revenue despite having lower sales volume than Arabica.
- **Arabica** recorded the highest quantity sold with 947 units.
- **52% of customers** do not use a loyalty card, indicating an opportunity to increase loyalty programme participation.

## 🛠️ Tools & Skills
**Excel**
* Power Query & Data Cleaning
* PivotTables & PivotCharts
* Slicers & Data Analysis
* KPI Reporting

**Power Query**
* Data Cleaning
* Merge Queries
* Replace Values
* Data Transformation
* Calculated Columns

**Analysis**
* Sales & Revenue Analysis
* Product Performance
* Customer Loyalty
* Trend Analysis
* Business Insights

## Project Workflow
Raw Data → Data Preparation → Power Query → Merge Tables → Select Relevant Columns → Standardise Values → Calculate Revenue → PivotTables → Dashboard → Business Insights
￼

## Explore the Dashboard
This project uses Excel and Power Query to transform raw sales data into an interactive dashboard. The dashboard includes data cleaning, PivotTables, PivotCharts, slicers, and KPI analysis to help users explore sales performance and identify key trends.

For questions or further discussion, feel free to connect with me on LinkedIn: www.linkedin.com/in/irdina-haziqah-termiti 
