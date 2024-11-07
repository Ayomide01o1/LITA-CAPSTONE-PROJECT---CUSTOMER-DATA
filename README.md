# LITA-CAPSTONE-PROJECT---CUSTOMER-DATA

## INTRODUCTION
This repository contains data and analysis for evaluating the sales performance of a retail store. The goal is to provide insights into key areas such as top-selling products, regional performance, and monthly sales trends.

## Dataset Description:

- Subscription type
- Subscription information (Customer ID, subscription type, revenue)
- Regional information ( region)
- Date information (date, month, quarter, year)

## Key Insights:

1. Top subscription type
2. Number of customers per region
3. Monthly subscription trends
4. Total revenue by subscription type
5. Average subscription duration


## DAX Formulas:
1. SELECT TOP 3 
  Region,
  COUNT(CustomerID) AS                CancellationCount
  FROM 
  TABLE_NAME
  WHERE 
  Canceled = 1
  GROUP BY 
  Region
  ORDER BY 
  CancellationCount DESC;



## Tools Used:

 -Power BI
 1. Visualization 
 -Microsoft Excel
1. Analysis
2. Visualization 
 -SQL server
1. SQL query writing and analysis 
