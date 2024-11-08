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


## DAX FUNCTIONS/QUERIES:
1. SELECT TOP 3 
  Region,
  COUNT(CustomerID) AS
   CancellationCount
  FROM 
  TABLE_NAME
  WHERE 
  Canceled = 1
  GROUP BY 
  Region
  ORDER BY 
  CancellationCount DESC;
2. SELECT TOP 1
SubscriptionType,
COUNT(CustomerID) AS Totalcustomers
FROM
[dbo].[Customer]
WHERE 
Canceled=0
GROUP BY
SubscriptionType
ORDER BY 
Totalcustomers DESC;


## Tools Used:
 -Power BI
 1. Visualization
 (https://github.com/user-attachments/assets/2cb2da77-4dc2-4a17-8763-77932e39e880)

 -Microsoft Excel
1. Analysis
2. Visualization
(https://github.com/user-attachments/assets/3978bfd8-d610-43f7-bd35-9b36aaaac023)

 -SQL server
1. SQL query writing and analysis 
