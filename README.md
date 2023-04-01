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
The Adventure Works 2019 database was used for this project. This fictional company’s database was created by Microsoft and can be downloaded [here] (https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorks2019.bak)
