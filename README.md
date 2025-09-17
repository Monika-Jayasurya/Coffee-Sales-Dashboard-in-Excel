☕Coffee Sales Analysis


📌 Project Overview

This project analyzes coffee sales data by combining multiple tables (Orders, Customers, and Products) into a unified dataset using Excel formulas (XLOOKUP, INDEX, MATCH, and IF).
The goal was to create an interactive dashboard that provides insights into customer behavior, product performance, and sales distribution.

📂 Dataset Structure

| Orders Table | Customers Table | Products Table |
| ------------ | --------------- | -------------- |
| Order ID     | Customer ID     | Product ID     |
| Order Date   | Customer Name   | Coffee Type    |
| Customer ID  | Email           | Roast Type     |
| Product ID   | Phone Number    | Size           |
| Quantity     | Address Line 1  | Unit Price     |
|              | City            | Price per 100g |
|              | Country         | Profit         |
|              | Postcode        |                |
|              | Loyalty Card    |                |


⚙️ Data Preparation

* Enriched the Orders Table by adding columns from Customers and Products using:

* XLOOKUP to fetch customer & product details

* INDEX + MATCH for exact row & column matches

* IF for handling missing/invalid lookups

** Final enriched dataset included: **(All In ONE Sheet)

Customer Name, Email, Country

Coffee Type, Roast Type, Size, Unit Price

Sales (Quantity × Unit Price)

Coffee Name Type, Roast Type Name

Loyalty Card status

📊 Analysis & Pivot Tables

**1. **Sales by Coffee Type****
   
![Sales by Coffee type](https://github.com/user-attachments/assets/a23a7504-2c5f-46b6-bbe5-92bea647f0e8)

**2. Pivoted by Year & Month (from Order Date)**

Table Provided in Excel Sheet - Total Sales

Compared sales of Arabica, Excelsa, Liberica, and Robusta

**3.Sales by Country**

![Sales by Country](https://github.com/user-attachments/assets/48799aa5-b72b-4b11-9439-5fc2f8ea5ff8)

Summarized total sales per country

**4. Top 5 Customers**

![Top 5 Customers](https://github.com/user-attachments/assets/c0234c37-3fd1-43d5-9169-ae72ac34e5af)

Ranked by total sales

**5. Visualized with a bar chart for Sales by Loyalty card**

![Loyalty Card](https://github.com/user-attachments/assets/24acaa78-0f46-4981-b814-6831370fae7a)

Loyalty Card Impact on Sales:

> Customers without a loyalty card generated $24,216.41 in sales.

> Customers with a loyalty card generated $20,917.85 in sales.

> Total sales amounted to $45,134.26.

Insight: While loyal customers contribute significantly, non-loyal customers currently account for a slightly higher share of total sales. 
This suggests potential to further leverage loyalty programs to boost revenue.


📈 Interactive COFFEE SALES Dashboard Features

![COFFEE SALES DASHBOARD](https://github.com/user-attachments/assets/542ffc8d-c54d-4147-9ff9-022206859734)

* Built an interactive Excel dashboard with the following:

* Total Sales overview

* Sales trend by month/year

* Sales by coffee type (slicers for Roast Type, Size, Loyalty Card)

* Sales by country

* Top 5 Customers (bar chart)

**🛠️ Tools & Skills Used**

Microsoft Excel (Pivot Tables, Charts, Dashboards)

Functions: XLOOKUP, INDEX, MATCH, IF

Data Cleaning & Transformation

Interactive Dashboard Design

📌 Key Insights

* Identified top-performing coffee types across time periods

* Highlighted country-wise sales contribution

* Recognized loyal customers and their impact on revenue

* Built a scalable template for future sales analysis

✅ This project showcases strong data wrangling, Excel formula expertise, and dashboard visualization skills for business reporting.
