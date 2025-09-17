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

![Sales by Country](https://github.com/user-attachments/assets/de04cff0-e994-485a-8de3-90cb443777df)

Summarized total sales per country

**4. Top 5 Customers**

![Top 5 Customers](https://github.com/user-attachments/assets/c0234c37-3fd1-43d5-9169-ae72ac34e5af)

Ranked by total sales

**5. Visualized with a bar chart for Sales by Loyalty card**

![Loyalty Card](https://github.com/user-attachments/assets/24acaa78-0f46-4981-b814-6831370fae7a)

**Loyalty Card Impact on Sales:**

> Customers without a loyalty card generated $24,216.41 in sales.

> Customers with a loyalty card generated $20,917.85 in sales.

> Total sales amounted to $45,134.26.

Insight: While loyal customers contribute significantly, non-loyal customers currently account for a slightly higher share of total sales. 
This suggests potential to further leverage loyalty programs to boost revenue.


📈 Interactive COFFEE SALES Dashboard Features

![COFFEE SALES DASHBOARD](https://github.com/user-attachments/assets/14da15db-e8c9-4a37-8625-c5ec834d08e2)




*** Built an interactive Excel dashboard with the following:**

* Total Sales overview
* Sales trend by month/year
* Sales by coffee type (slicers for Roast Type, Size, Loyalty Card)
* Sales by country
* Top 5 Customers (bar chart)

**🛠️ Tools & Skills Used**

* Microsoft Excel (Pivot Tables, Charts, Dashboards)
* Functions: XLOOKUP, INDEX, MATCH, IF
* Data Cleaning & Transformation
* Interactive Dashboard Design

📌 Key Insights

* Identified top-performing coffee types across time periods
* Highlighted country-wise sales contribution
* Recognized loyal customers and their impact on revenue
* Built a scalable template for future sales analysis

**Conclusion & Recommendations:**

**Current Observation:**

Total sales: $45,134.26
* Non-loyalty customers contribute slightly more ($24,216.41) than loyalty customers ($20,917.85).
* Loyal customers are already a significant source of revenue but not the majority.

**Insights:**

* There is room to improve sales among loyalty card holders. Encouraging more customers to join the loyalty program can help increase repeat purchases.
* Non-loyalty customers are currently driving higher sales. Strategies to convert them into loyal customers could further increase overall revenue.
* Analyzing top-performing coffee types and targeting promotions to countries or segments with lower sales could boost overall performance.

**Recommendations for Sales Improvement:**

* Expand loyalty program benefits to attract more customers.
* Promotional campaigns targeted at non-loyalty customers to encourage repeat purchases.
* Upselling or cross-selling popular coffee types based on sales trends.
* Country-wise marketing strategies to increase sales in underperforming regions.

**Overall: The sales performance is healthy, but focusing on loyalty growth, targeted promotions, and customer conversion strategies can further improve revenue.
**


✅ This project showcases strong data wrangling, Excel formula expertise, and dashboard visualization skills for business reporting.
