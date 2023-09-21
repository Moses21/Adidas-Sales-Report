# Adidas Products Sales Analysis 
![](adidas-store.png)

## Introduction
This is a Microsoft Excel dashboard project on sales analysis of an imaginary brand company called **Adidas Store**. 
The dataset contains sales data of 9,648 customers of **Adidas Store** who place orders from year 2020 to 2021 in United States of America, including the invoice date, retailer, states, region, city, product, price per unit, total revenue, and sales method.

My goal in this project to help stakeholder etc to have insight about customer demographics, product performance, revenue made and sales channel performance to enable **Adidas Store** to make profitable data-driven decisions.

**_Disclaimer_**:- _All datasets and reports do not represent any company, institution or country, but just a dummy dataset to demonstrate capabilities of Microsoft Excel._

## Problem Statements
The following business questions have been presented to enable the marketing team at **Adidas Store** to understand the sales which were made in 2020 to 2021.

1. Which products conttribute more to the revenue?
2. Which states and city should we push more products?
3. What is the peak month for sales in 2020 and 2021?
4. Which sales methods are performing well?

## Microsoft Excel skills/concepts demonstrated 
- Data cleaning
- Excel formulas (DATE, SUM etc)
- Cell referencing
- Pivot tables
- Slicers
- Data visualization
- Dashboard buiding

## Data Cleaning
- The dataset was imported into Microsoft Excel using the **Get data** option in the data tab. Here is how I cleaned the data.
- Column datatypes were validated appropriately  – E.g. revenue column was formatted to have currency format.
- To change the Invoice Date column, Invoice Date which was on in number data type, to the ‘date’ data type, a new column was created, and the formula below was used to fill the new 
  column with the data that can be changed to the date data type.
  
  ```html
  =DATE(YEAR(C2), MONTH(C2), DAY(C2))
  ```
- The cell reference ID, `C2` contains the Invoice Date record in the original column. The formula converts the number in cell C2 to a date format and column `Invoice_Date` was created. 
  The rest of the rows were auto-filled by Excel accordingly.

