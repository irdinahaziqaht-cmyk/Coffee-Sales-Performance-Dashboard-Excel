# Coffee-Sales-Performance-Dashboard-Excel
Transforming raw coffee sales data into actionable business insights using Excel, Power Query, and an interactive dashboard.

Overview
This project analyses coffee sales data using Microsoft Excel and Power Query to understand sales performance, product performance, and customer loyalty.
The project covers data preparation, transformation, analysis, and dashboard development using an interactive Excel dashboard.

Project Objectives
* Analyse coffee sales performance
* Track revenue and sales trends
* Compare coffee type performance
* Analyse customer loyalty card usage
* Identify key sales patterns through an interactive dashboard

Data Preparation
The dataset contains three related tables: Orders, Customers, and Products.

Power Query
* Removed unused columns and cleared existing filters
* Imported all three tables into Power Query
* Renamed the queries for easier management
* Merged Orders + Customers using Customer ID
* Merged the main data with Products using Product ID
* Selected relevant product information: Coffee Type, Roast Type, Size, and Unit Price

Value Standardisation
Coffee Type
Rob ->	Robusta
Ara	-> Arabica
Exc	-> Excelsa
Lib	-> Liberica

Roast Type
D -> Dark
L	-> Light
M	-> Medium
The Replace Values function in Power Query was used to standardise these categories.

Revenue Calculation
Created a new Revenue column:
Revenue = Quantity × Unit Price
The calculation was created using Add Column → Standard → Multiply.
The final dataset was then loaded back into Excel for PivotTable analysis and dashboard development.

📊 Dashboard
Key Metrics
* Total Revenue: $45,134.26
* Total Quantity Sold: 3,551
* Total Customers: 1,000

Revenue by Month
Tracks monthly revenue across different coffee types and highlights changes in sales performance throughout the year.

Revenue vs Quantity Sold
Compares revenue and quantity sold across Arabica, Excelsa, Liberica, and Robusta.
Key insight: Arabica recorded the highest quantity sold, while Excelsa generated the highest revenue.

Customer Loyalty
48% of customers use a loyalty card, while 52% do not.

Loyalty Card Usage by Year
Shows the number of loyalty card users and non-users across different years.

Interactive Filters
The dashboard can be filtered by:
* Year
* Country
* Coffee Type
* Roast Type
* Size
Users can select the relevant filters to drill down into specific sales segments and compare performance.

💡 Key Business Insights
* Excelsa generated the highest revenue, despite having lower sales volume than Arabica.
* Arabica recorded the highest quantity sold with 947 units.
* 52% of customers are not loyalty card users, indicating room to increase loyalty programme participation.
* Revenue performance varies across months and coffee types, with some periods showing stronger sales than others.

🛠️ Tools & Skills
Excel
* Power Query & Data Cleaning
* PivotTables & PivotCharts
* Slicers & Data Analysis
* KPI Reporting

Power Query
* Data Cleaning
* Merge Queries
* Replace Values
* Data Transformation
* Calculated Columns

Analysis
* Sales & Revenue Analysis
* Product Performance
* Customer Loyalty
* Trend Analysis
* Business Insights

Project Workflow
Raw Data → Data Preparation → Power Query → Merge Tables → Select Relevant Columns → Standardise Values → Calculate Revenue → PivotTables → Dashboard → Business Insights
￼

Explore the Dashboard
This project uses Excel and Power Query to transform raw sales data into an interactive dashboard. The dashboard includes data cleaning, PivotTables, PivotCharts, slicers, and KPI analysis to help users explore sales performance and identify key trends.

For questions or further discussion, feel free to connect with me on LinkedIn: www.linkedin.com/in/irdina-haziqah-termiti 
