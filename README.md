# Adventure Works Cycles Report
![](intro.png)
## Introduction
This is a Power BI project on Adventure Works 2019 sample database, which is a fictional company’s database created by Microsoft for educational and testing purposes. The goal of the project is to identify products with the highest and lowest turnover rate, observe yearly overall sales, and identify customer trends and preference.
## Problem statement
To use the business database to identify:
- Which products have the highest turnover rate.
- Which products have the lowest turnover rate.
- If overall sales increased yearly.
- Customer’s growth trend over the years and shopping preference.
## Skills demonstrated
The following SQL Server Management Studio skills were incorporated:
- Importing a database.
- Generating a database diagram.
- Data wrangling with SQL.

The following Power BI skills were also incorporated into this report:
- DAX – I created DAX columns to use as a primary date column, then extracted columns including Date, Day, Day Number, Month Number, Quarter, Year and Month columns.
- Modelling – Three tables were loaded into Power BI (1 dimension table and 2 facts table) while the Calendar and ‘CustomerFirstOrders’ Tables were generated using the New Table, Power Query and DAX functions. The data was modelled with appropriate primary key and foreign key relationships.
- Filters – I used the Filter pane to filter out Top and Bottom Products subcategories by sales to give insight to the best and worst performing products.
- Slicers – I used Slicers to create a more dynamic report that filters result through years and order continents.
- Bookmarks – I used Bookmarks to manage views on the report.
- Tooltips – I created dynamic tooltips to help interpret the visuals better.
- Quick measure – I used Quick measure to create custom calculations faster.
- Page navigation & Buttons – I used buttons to aid page navigation and improve user interactivity.
- Forecast – I used Forecast to predict sales trend and patterns for the following year.
- Drill through – I created a drill through page to help users gain deeper insight and a better understanding of the underlying data.

## Data sourcing
The Adventure Works 2019 database was used for this project. This fictional company’s database was created by Microsoft and can be downloaded [here](https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorks2019.bak).

## Data transformation
The database was imported into SQL Server Management Studio and then queried to obtain the needed data from the schemas and tables. The following schemas and Tables were queried: 
Sales.SalesOrderheader, Sales.SalesOrderDetail, Sales.Customer, Sales.SalesTerritory, Purchasing.ShipMethod, Production.Product, Production.ProductCategory, and Production.ProductSubcategory.

Here's the link to my SQL [query](https://github.com/emmywritescode/SQL-Queries/blob/main/Adventure%20Works%20Cycles%202019.sql).

## Modelling
The data was modelled with the appropriate primary key and foreign key relationships from the tables. Overall, there are three (3) dimensions tables and two (2) facts tables. Two tables created named ‘Calendar’ and ‘CustomerFirstOrders’ tables were generated using New Table, Power Query and DAX functions. The Orders table was joined to the Products table in a one-to-many relationship. The Calendar table was also joined to the Orders table in a one-to-many relationship while the Customers table was joined to the CustomersFirstOrders table in a one-to-one relationship.

![](data_model.png)

## Analysis and Visualizations
The report comprises 6 pages
1. Periodic Sales Report
2. Revenue/Sales Trend and Forecast
3. Customer Details Report
4. Product Category and Subcategory Report
5. Products by Sales
6. Insights

You can interact with the report here: _link coming soon_

**Features:**
- The Filter icon removes current filters applied to the report.
- The Direction arrow navigates to the next page.
- The Web icon shows hidden links to my social handles.
## Analysis
**Periodic Sales Report:**

![](periodic_sales.png)
- The company generated over $109M in sales over the entire period with most sales coming from 2013 fiscal year.
- Daily sales averaged between around $900 each day of the week and more than 31K total transactions were made.

**Customer Details Report:**

![](customer_details.png)
- More than 19K customers made purchase from the company.
- Customers placed more orders online than offline.
- Most customers are from Southwest territory.
- Customers increased over the years but mostly in 2013.





