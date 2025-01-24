# Coffee Sales Analysis Project

## Table of Contents

- [Overview](#Project-Overview)
- [Data Sources](#Data-Sources)


### Overview

This project focuses on analyzing coffee sales data to extract meaningful insights and present them in an interactive and dynamic dashboard. The dataset, sourced from GitHub, includes various types of coffee sales across multiple countries. 
The primary goal is to analyze sales trends, identify key customers, and provide a clear visual representation of the findings.



### Project Workflow

 1- Data Acquisition

  The dataset was obtained from GitHub, ensuring a reliable source of information for analysis.


2- Data Inspection

 The dataset was carefully inspected to understand its structure and identify any inconsistencies.
 

 3- Data Cleaning

 Cleaning steps were performed to ensure the data was accurate and ready for analysis.
 

 4- Data Analysis

 A pivot table was used to analyze the data and answer key business questions.
 

 5- Data Visualization

 Pivot charts were created to visualize trends and insights effectively.
 

 6- Dynamic Dashboard

 An interactive dashboard was built to present findings and allow dynamic exploration of the data.


 

 ### Key Questions Addressed:

 1- What are the total sales over time?
 
 2- How are the sales distributed by country?
 
 3- Who are the top 5 customers by sales?
 

 
### Tools Used

- Microsoft Excel (Pivot Tables, Pivot Charts, Dynamic Dashboard)

  

### Data Cleaning/Preparation

  1- Data Gathering:
  
  Customer Information: Collected Customer Name, Email, Country, and Loyalty Card using the XLOOKUP function.
Product Information: Gathered Coffee Type, Roast Type, Size, and Unit Price using a combination of INDEX and MATCH functions.

2- Calculated Fields:

 Created a new column for Sales by multiplying Unit Price by Quantity.

 3- Data Cleaning:

 - Duplicate Check: Verified there were no duplicate entries in the dataset.
 - Converted coffee-type abbreviations into full names using the IF function.
 - Transformed roast-type names into full descriptions.
 - Standardized the Month column to show months as letter abbreviations (e.g., Jan, Feb) to avoid confusion.
 - Formatted the Size column to display values with the kg metric unit.
 - Converted Unit Price and Sales columns to U.S. Dollars for consistency.
 - Converted the dataset into an actual table to allow automatic updates when changes are made.


### Data Analysis

- Used Pivot Tables to answer key business questions:

Total Sales Over Time
Sales by Country
Top 5 Customers by Sales

- Customized Pivot Tables and created corresponding Pivot Charts for effective visualization.

