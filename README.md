# Sales Analysis

## Table Contents

-  [Project Overview](#project-overview)
-  [Data Sources](#data-sources)
-  [Tools](#tools)
-  [Data Cleaning/Preparation](#data-cleaningpreparation)
-  [Explortory Data Analysis](#exploratory-data-analysis)
-  [Data Analysis](#data-analysis)
-  [Results](#results)

### Project Overview

This Data Analysis project aims to provide an insights into the United States Sales Perfomance.By analyzing various aspects of Sales data,customer data and product data,we seek to identify trend,make data-driven recommendations and gain deep understanding of the sales region wise in United States.

!Dashboard
![Sales Dashboard](https://github.com/praveenaK15/Sales-analysis/assets/164007130/fd741817-b7e7-4f8b-bb96-3d6fbc7edf35)


### Data Sources

1. **Sales data**: The primary data set for this analysis is the "Sales.xlsx",containing detailed information about sales made by customers.
2. **Customer data**: The secondary data set for this analysis is the "Customer.xlsx",containing detailed information about the customers.
3. **Product data**: The tertiary data set for this analysis is the "Product.xlsx",containing detailed information about the products ordered by customers.

### Tools

  - Excel: Data Cleaning
  - SQL: Data Analysis
  - Tableau: Creating Reports

### Data Cleaning/Preparation

performed the following task:
1. Data loading and inspection.
2. Handling null values.
3. Data Cleaning and Formatting.

### Exploratory Data Analysis

 EDA involves exploring the data to answer key questions like:
 1. what is the region-wise sales?
 2. which year has the highest sales?
 3. which state has highest number of profits?
 4. which products are top sellers?

### Data Analysis

Including some interesting code/features worked with:

```sql

  SELECT*FROM SALES
  WHERE Ship mode='First Class'
  ORDER BY customer_id;

```

### Results

The analysis results are summarized as follows:
1. East region have the highest number of profit.
2. The sales have been increasing over the years.
3. Technology category have the highest number of sales.


