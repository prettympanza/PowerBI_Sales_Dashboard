Sales Performance Dashboard | Power BI

Overview

This project showcases an interactive Power BI sales dashboard built to analyse revenue, profitability, product performance, geographic trends, and payment behaviour using transactional sales data.
The dashboard is designed for executive decision-making and demonstrates end-to-end power BI skills: data modelling, DAX, and insight generation.


Objectives

•	Track overall sales and profit performance

•	Identify top and underperforming products

•	Analyse regional sales distribution

•	Compare revenue vs profitability


Data

The model follows a star schema with two CSV files:

•	Orders (Dimension Table)
Order ID, Order Date, Customer, City, State

•	Details (Fact Table)
Order ID, Sales Amount, Profit, Quantity, Category, Sub-Category, Payment Mode
Data Model

•	One-to-Many: Orders [Order ID] → Details [Order ID]

•	Optimised for Power BI best practices


Key DAX Measures

•	Total Sales · Total Profit · Profit Margin % · Total Orders · Running Total Sales · Month-on-Month (MoM) Growth % · Year-on-Year (YoY) Growth % · Product Sales Ranking


Dashboard Features

•	KPI Cards: Sales, Profit, Margin, Orders

•	Trend Analysis: Monthly sales 

•	Product Analysis: Category & sub-category performance

•	Geographic Analysis: State & city-level sales

•	Payment Analysis: Customer payment preferences

•	Interactivity: Slicers and drill-through pages


Key Insights

•	Revenue is concentrated in the electronics and furniture product categories.

•	Higher sales in Clothing and Electronics are associated with higher profits.

•	Sales are concentrated in urban cities, while rural areas contribute significantly less revenue.

•	Cash on delivery payment method is the most widely used.

•	Clear seasonality is present, with stronger sales at the beginning and end of the year.


Tools

•	Power BI Desktop

•	DAX

•	Power Query

•	CSV data sources


Skills Demonstrated

•	Data modelling (star schema)

•	DAX 

•	Data cleaning & transformation

•	Business-focused data visualisation

•	Insight-driven reporting




