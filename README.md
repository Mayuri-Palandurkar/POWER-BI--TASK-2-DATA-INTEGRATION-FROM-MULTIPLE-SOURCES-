# POWER-BI--TASK-2-DATA-INTEGRATION-FROM-MULTIPLE-SOURCES-

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: MAYURI PALANDURKAR

**INTERN ID**: CT04WH103

**DOMAIN**: POWER BI

**DURATION**: 1 MONTH

**MENTOR**: NEELA SANTOSH

# DESCRIPTION OF TASK 2: DATA INTEGRATION FROM MULTIPLE SOURCES 

**Objective**:
To integrate two different datasets (Superstore Sales and Customer Orders) into Power BI and create a unified report using data merging, cleaning, and relationship building.

**Tools & Skills Used**:
Power BI Desktop
Power Query Editor
Data Merging using Merge Queries
Data Cleaning & Null Handling
Creating Relationships Between Tables

**Steps Followed to Complete Task 2**:
**Step 1**: Loaded Two Datasets
Superstore Sales.csv – contains Order ID, Product, Sales, Profit, Region, Customer Segment.
Customer Orders.xlsx – includes Order ID, Order Total, Customer Ratings, Order Count.
Used Home → Get Data to load both files into Power BI.

**Step 2**: Opened Power Query Editor
Opened Transform Data to clean and merge datasets.
Renamed tables for clarity:
Sales
CustomerOrders

**Step 3**: Merged Queries
Clicked Home → Merge Queries.
Chose Sales as the primary table and CustomerOrders as the secondary.
Merged using Order ID (common column in both datasets).
Join type: Left Outer Join (keeps all rows from Sales table).

**Step 4**: Expanded Columns from Merged Table
Clicked the Expand icon on the merged column.
Selected important fields from Customer Orders:
Order Total
Order Count
Average Rating
These fields were added to the Sales table.

**Step 5**: Handled Missing Data
Removed nulls from merged fields using:
Remove Rows → Remove Blank Rows
Replace Values (if applicable)

**Step 6**: Created Relationships
Verified relationships in Model View.
Ensured Order ID connects both tables (if tables were kept separate).

**Result**:
You now have a combined, enriched dataset in Power BI that links sales data with customer behavior metrics like order totals and ratings.
This integration allows for deeper analysis, such as:
Finding patterns between customer ratings and profitability
Segmenting by customer order count
Analyzing sales and customer behavior in one dashboard

# OUTPUT:


