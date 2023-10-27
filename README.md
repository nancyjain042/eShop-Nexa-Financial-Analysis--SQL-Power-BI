# eShop-Nexa-Financial-Analysis--SQL-Power-BI

## Problem Statement:

This project is focused on extracting valuable insights from a comprehensive dataset that includes sales records, store information, sales team data, regional statistics, product details, and customer information. The primary goal is to facilitate well-informed business decisions by examining sales patterns, geographic influences, sales team performance, and product performance.

## About the Dataset:

The dataset comprises several tables:

**Fact Table**:

OrderNumber: A unique identifier for each order.

Sales Channel: The channel through which the sale was made (e.g., In-Store, Online, Distributor).

WarehouseCode: Code for the warehouse where products were sourced.

ProcuredDate: Date when the products were procured.

OrderDate: Date when the order was placed.

ShipDate: Date when the products were shipped.

DeliveryDate: Date when the products were delivered.

CurrencyCode: Currency code for the transaction.

_SalesTeamID: A unique identifier for the sales team associated with the sale.

_CustomerID: A unique identifier for the customer.

_StoreID: A unique identifier for the store.

_ProductID: A unique identifier for the product.

Order Quantity: The quantity of products ordered.

Discount Applied: The discount applied to the order.

Unit Price: The unit price of the product.

Unit Cost: The cost per unit of the product.

**Sales Team Table**:

_SalesTeamID: A unique identifier for the sales team.

Sales Team: The name of the sales team.

Region: The region to which the sales team belongs.

**Region Table**:

StateCode: The code for the state.

State: The full name of the state.

Region: The region to which the state belongs.

**Customers Table**:

_CustomerID: A unique identifier for the customer.
Customer Names: The name of the customer.


## Key Objectives:

The primary project objectives include:

**Sales Analysis**: Analyze sales data to identify trends, understand sales channel performance, evaluate product sales, and assess the impact of discounts on revenue.

**Geographic Analysis**: Examine the influence of geographic factors, including city, state, and region, on sales performance. Analyze demographic data to understand potential correlations with sales.

**Sales Team Performance**: Evaluate the performance of sales teams, their contributions to overall sales, and regional variations in sales trends.

**Product Analysis**: Investigate product sales data to identify top-performing products and understand their impact on overall revenue.

## Data Processing:

In the data processing phase, the following steps will be taken:

**Data Import**: Load the dataset into a SQL database, creating tables for the Fact Table and dimension tables.

**Data Cleaning**: Address any missing values, errors, or inconsistencies in the data to ensure data accuracy.

**Data Transformation**: Create relationships between tables using primary and foreign keys to enable comprehensive analysis.

**Data Analysis**:

This phase involves conducting SQL queries to perform sales analysis, geographic analysis, sales team evaluation, and product analysis. Data from various tables will be aggregated and joined to derive meaningful insights.

**Data Processing in Power BI**:

In this phase, Power BI will be used to:

**Data Visualization**: Connect Power BI to the SQL database to create interactive visualizations. Design dashboards, charts, and tables to effectively present the findings in an intuitive and informative manner.
