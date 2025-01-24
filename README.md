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

1. Data loading in MySQL database
2. A backup Creation ( a copy of the original table was made to avoid any accidental data loss. )
3. Removing Duplicates - 
   ( used a window function and a common table expression (CTE) to identify and remove duplicate records, as MySQL didn’t support the DELETE function for this purpose - 
Created a new table to store the cleaned data, and added a unique identifier column (row_num) for each row. )

4. Data Standardizing - ( removed extra spaces in the company name column - 
Corrected spelling errors (e.g., “Crypto”) - 
Converted date values into a standard format and changed the column type from text to date for consistency. )

5. Handling null and blank values ( converted any blank values to NULL for easier handling - 
Replaced NULL values with appropriate match values from the same company and location - 
Removed irrelevant records that were unnecessary for analysis. )

 6. Column Cleanup ( removed unneeded columns that didn’t contribute to the analysis. )
