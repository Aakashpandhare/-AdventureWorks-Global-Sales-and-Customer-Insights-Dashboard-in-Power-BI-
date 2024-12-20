# "AdventureWorks Global Sales and Customer Insights Dashboard in Power BI"

## Project Overview
This project involved building a comprehensive business intelligence dashboard in Microsoft Power BI for AdventureWorks, a global manufacturing company specializing in cycling equipment and accessories. The dashboard provides actionable insights into sales, revenue, profit, returns, and customer behavior, enabling stakeholders to make data-driven decisions.

The dataset was sourced from Microsoft’s AdventureWorks sample databases. The project followed an end-to-end BI development process starting from data import and cleaning to interactive dashboard creation and optimization.

## About AdventureWorks
AdventureWorks operates globally, with customers spread across six countries: Australia, Canada, France, Germany, the United Kingdom, and the United States. The company’s customer data includes profiles with demographics such as date of birth, annual income, education level, number of children, occupation, and homeowner status.

The dataset encompasses sales and returns data from 01/01/2020 to 30/06/2022, enabling trend analysis and performance comparisons across regions, products, and customer segments.

## Problem Statement

The AdventureWorks management team sought a solution to address the following challenges:

Tracking key performance indicators (KPIs): Revenue, profit, sales orders, and return rates.

Regional performance comparison: Identifying strengths and weaknesses across different territories.

Product-level trend analysis: Determining which products generate the most revenue or have the highest return rates.

Customer insights: Identifying high-value customers and exploring customer behavior trends.

The goal was to deliver a user-friendly, interactive Power BI dashboard to meet these requirements and support strategic decision-making.

## Data Overview

The project dataset consisted of the following:

Data sources: Eight CSV files, including tables for sales, returns, customers, products, and sales territories.

Record count: Approximately 60,000 records across all tables.

Import mode: Data was imported into Power BI using the Import Mode, enabling efficient and performant analysis.

## Data Preparation

The raw data required cleaning and transformation to ensure accuracy, consistency, and usability.

## Power Query Transformations:
Renamed columns for readability and standardization.

Ensured correct data types for fields (e.g., currency, dates, and numeric values).

Created a rolling calendar table using Power Query M code for time intelligence calculations.

Removed unnecessary columns and filtered irrelevant data to improve performance.

Verified data quality, ensuring no missing or erroneous values.

## Data Modeling

The data modeling stage involved creating a structured and optimized schema to facilitate analysis.

## Approach:

Snowflake Schema: Fact tables (Sales Data, Returns Data) were connected to related dimension tables (Products, Customers, Dates, and Territories).

Relationships: Established one-to-many relationships between tables, ensuring accurate aggregations.

Optimizations: Assigned appropriate cardinality and cross-filtering directions to optimize performance.

### Advanced Features:

Utilized field parameters to dynamically switch between metrics on visuals.

Enabled drill-through functionality to navigate from summary-level data to detailed product or customer insights.

## DAX Measures

Custom DAX measures were created to enable advanced analysis and KPIs.

Examples include:
Revenue, Profit, and Total Orders: Core KPIs for executive insights.

Rolling Metrics: Used date functions (DATESINPERIOD, DATEADD) to calculate rolling 90-day revenue and profit.

What-If Analysis: Created a parameter to test the impact of a 10% increase or decrease in product prices on profitability.

Custom Measures: Built dynamic calculations for previous month’s revenue, profit, returns, and averages.

## Dashboard Design

The Power BI dashboard was designed with four key pages, each focusing on a specific aspect of AdventureWorks’ performance:

## 1. Executive Dashboard:
Purpose: Provide a high-level summary of company-wide KPIs.
Visuals:
    Gauges for revenue, profit, and return rates.
    
    Line charts for trend analysis of orders and revenue over time.
    
    Top-selling products and top-performing territories.
     
    A slicer panel for filtering by year and region.
    
Interactivity: Drill-through functionality enabled for product-specific analysis.

## 2. Map View:
Purpose: Visualize geographic distribution of orders.

Visuals: Map chart with bubble sizes indicating total orders per country.

Key Insights:

The United States leads in orders and revenue.

Australia has the highest revenue per customer, suggesting premium pricing or loyal customers.

## 3. Product Detail Page:
Purpose: Dive deeper into product performance metrics.
Visuals:

Decomposition tree to identify drivers of revenue or returns.

What-If parameter for testing price adjustments.

Bar charts comparing product-level KPIs (revenue, profit, return percentage).

Key Insights: Identified products with high returns (e.g., cycling shorts) and potential defects.

## 4. Customer Detail Page:
Purpose: Analyze customer behavior and demographics.
Visuals:

Donut charts for customer segmentation (occupation, income).

Tables showcasing top 100 customers by revenue and orders.

Trends in customer acquisition over time.

Insights: Revealed revenue concentration among a small group of high-value customers.

## Advanced Features

The dashboard incorporated several advanced Power BI functionalities:

Smart Narrative Visual: Automatically generated text summaries of key insights.

Key Influencers Visual: Analyzed factors driving returns and profitability.

Top N Filtering: Highlighted top products and customers.

Interactive Elements:

Slicers for year and geography.

Buttons for page navigation.

Drill-through for granular insights on products and customers.

## Insights

## Revenue Trends:
Total revenue: $24.9M; Total profit: $10.5M.

A significant dip in mid-2020 likely reflects the impact of COVID-19, with recovery starting late 2020.

Exceptional performance in December 2021, suggesting potential seasonal promotions.

Product Analysis:
Tires and tubes generate the most orders.

Cycling shorts have the highest return rates, indicating quality issues.

Sports helmets are high-revenue generators despite above-average return rates.

Customer Insights:
Australian customers have the highest average revenue per customer ($2,131).

Top 5 customers contribute significantly to revenue with fewer than 7 orders.

Geographic Performance:
The U.S. dominates in terms of total orders and revenue.

Untapped markets in Asia, Africa, and South America present growth opportunities.

## Conclusion

This project demonstrated the end-to-end process of building a robust, interactive Power BI dashboard to address real-world business challenges. Key takeaways include:

Comprehensive data transformation and modeling using Power Query and DAX.

The ability to drill down into insights across products, customers, and regions.

Advanced features like What-If analysis, smart narratives, and decomposition trees enhanced the decision-making experience.

This dashboard empowers AdventureWorks to monitor performance, identify opportunities, and address challenges effectively, showcasing my proficiency in Power BI for business intelligence solutions.

### Thank you !
