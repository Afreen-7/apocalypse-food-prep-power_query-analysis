# Apocalypse Food Prep – Power Query & Power BI Analysis

## Project Overview

This project analyzes the **Apocalypse Food Prep** dataset using **Microsoft Excel, Power Query, PivotTables, and Power BI**.

The project demonstrates an end-to-end data analysis workflow, starting from raw retail and sales data and transforming it into structured information for analysis and visualization.

The project covers:

* Data cleaning and transformation using Power Query
* Retail product price analysis
* Store and product comparisons
* Excel PivotTable analysis
* Power BI data modeling
* Product sales and revenue analysis
* Conditional formatting in Power BI
* Interactive data visualization

The analysis includes both **retail price observations** and **product sales data**, providing insights into product pricing and sales performance.

---

## Dataset

The project uses the **Apocalypse Food Prep** dataset.

The dataset includes information about products, prices, sales transactions, customers, and retailers.

### Retail Price Data

The retail price dataset contains price information collected from three major retailers:

* Costco
* Target
* Walmart

The price data covers the period from **January 2022 to April 2022**.

Products include:

* Bottled Water
* Canned Vegetables
* Dried Beans
* Duct Tape
* Flashlight
* Milk
* Rice
* Rope
* Water Filter

### Sales Data

The sales dataset contains information about products and customer transactions.

The Excel workbook includes the following sheets:

### 1. Apocalypse Store

Contains product-level information:

* Product ID
* Product Name
* Price
* Production Cost

### 2. Apocalypse Sales

Contains sales transaction information:

* Customer ID
* Customer
* Product ID
* Order ID
* Units Sold
* Date Purchased

### 3. Customer Information

Contains customer details:

* Customer ID
* Customer
* Address
* City
* State
* Zipcode

---

## Retailers

The retail price analysis covers:

* Costco
* Target
* Walmart

---

## Time Period

The retail price analysis covers:

**January 2022 – April 2022**

---

## Tools & Technologies

* **Microsoft Excel**

  * Data organization
  * PivotTables
  * Price summaries
  * Purchase overview

* **Power Query**

  * Data cleaning
  * Data transformation
  * Reshaping data
  * Structuring data for analysis

* **Power BI**

  * Data modeling
  * Data visualization
  * Conditional formatting
  * Product analysis
  * Sales analysis
  * Revenue analysis

---

# Part 1 – Power Query & Excel Analysis

## Data Preparation with Power Query

Power Query was used to transform the raw retail price data into a structured format suitable for analysis.

The transformed dataset contains fields such as:

| Column  | Description                    |
| ------- | ------------------------------ |
| Store   | Retailer name                  |
| Product | Food/preparation product       |
| Price   | Product price                  |
| Date    | Date associated with the price |

Power Query helped organize, clean, and restructure the source data before it was analyzed using Excel and Power BI.

---

## Excel Analysis

A PivotTable was created to summarize product prices by:

* Store
* Product
* Month
* Grand Total

The project also includes a **Purchase Overview** showing monthly and overall price totals for each retailer.

---

## Overall Store Totals

Based on the retail price analysis:

| Store           |   Total Price |
| --------------- | ------------: |
| Costco          |       $343.67 |
| Target          |       $374.17 |
| Walmart         |       $372.55 |
| **Grand Total** | **$1,090.39** |

These totals represent the **sum of recorded product-price observations** across the analyzed period. They should not be interpreted as total sales revenue.

---

## Power BI Data Model

The transformed data was brought into Power BI for further analysis and visualization.

The Power BI data structure includes fields such as:

* Location / Store
* Product
* Date
* Product Cost
* Sales information
* Customer information

This provides a foundation for comparing products, retailers, prices, sales, and revenue.

---

# Part 2 – Power BI Conditional Formatting

## Conditional Formatting Overview

The second stage of the project focuses on using **Conditional Formatting in Microsoft Power BI**.

The main purpose was to understand how conditional formatting can make Power BI tables and visualizations easier to read and interpret.

The dashboard focuses on comparing:

* Product prices
* Units sold
* Revenue

across different Apocalypse Food Prep products.

---

## Conditional Formatting Techniques

### Data Bars

Data bars were used to visually represent the magnitude of **Units Sold**.

This makes it easier to compare products without relying only on numerical values.

### Color Scales

Color scale formatting was applied to product **Price** values.

The color intensity provides a quick visual indication of relatively lower and higher prices.

### Icons

Icon-based conditional formatting was used to provide additional visual indicators for values.

Icons make patterns and differences easier to identify at a glance.

---

## Dashboard

The Power BI dashboard provides product-level analysis using:

* Product Name
* Product Price
* Units Sold
* Revenue

The visuals allow products to be compared based on their sales and financial performance.

### Product Sales Table

The table displays product information along with **Units Sold**.

Conditional formatting is applied to make numerical values more visually informative and easier to compare.

### Revenue Analysis

The dashboard also compares products based on:

* Units Sold
* Revenue

This helps identify products with higher sales volumes and revenue.

---

## Products Included in the Analysis

The dashboard includes products such as:

* Multitool Survival Knife
* Nylon Rope
* Duct Tape
* Stainless Steel Axe
* N95 Mask
* Weatherproof Jacket
* Water Purifier
* Backpack
* Waterproof Matches
* Solar Battery Flashlight

---

# Key Analysis Areas

The project focuses on questions such as:

* Which retailer has the lowest overall recorded price total?
* How do product prices differ between Costco, Target, and Walmart?
* Which products have the highest recorded prices?
* How do prices change from January through April?
* Which products show the largest price differences between retailers?
* Which products have the highest units sold?
* Which products generate the highest revenue?
* How can conditional formatting make product comparisons easier?
* How can transformed data be presented clearly for business decision-making?

---

# Project Objectives

The main objectives of this project were to:

1. Clean and transform raw data using Power Query.
2. Organize product, store, price, and date information.
3. Analyze retail prices across multiple stores and months.
4. Compare Costco, Target, and Walmart prices.
5. Create Excel PivotTables for price analysis.
6. Import transformed data into Power BI.
7. Create product-level sales and revenue analysis.
8. Practice conditional formatting in Power BI.
9. Improve data readability through visual formatting.
10. Present data in a clear and business-friendly format.

---

# What I Learned

Through this project, I practiced:

* Data cleaning and transformation using Power Query
* Organizing raw datasets for analysis
* Creating Excel PivotTables
* Analyzing product prices
* Comparing retailer performance
* Building Power BI reports
* Creating tables and visualizations
* Applying data bars
* Applying color scales
* Using icon-based conditional formatting
* Comparing product sales performance
* Analyzing revenue
* Improving the readability of data visualizations
* Presenting numerical data in a more intuitive way

---

# Dashboard Preview

The Power BI dashboard provides a visual comparison of product prices, units sold, and revenue using different conditional formatting techniques.

![Power BI Dashboard](dashboard.png)

---

# Dataset Structure

```text
Apocalypse Food Prep
│
├── Apocalypse Store
│   ├── Product ID
│   ├── Product Name
│   ├── Price
│   └── Production Cost
│
├── Apocalypse Sales
│   ├── Customer ID
│   ├── Customer
│   ├── Product ID
│   ├── Order ID
│   ├── Units Sold
│   └── Date Purchased
│
└── Customer Information
    ├── Customer ID
    ├── Customer
    ├── Address
    ├── City
    ├── State
    └── Zipcode
```

---

# Key Takeaway

This project demonstrates an end-to-end data analysis workflow using **Excel, Power Query, and Power BI**.

It shows how raw data can be cleaned and transformed, analyzed using PivotTables, and then presented through Power BI visualizations.

The project also demonstrates how **conditional formatting** can improve the readability of numerical data and make comparisons between products easier and faster.

Overall, the project showcases practical skills in **data preparation, data analysis, Power BI visualization, and business-oriented reporting**.

---

## Author

**Afreen Tariq**

BS Data Science | Data Analyst
