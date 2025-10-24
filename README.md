# Day04_Elevate-Lab-Task4
This repository contains Elevate Lab SQL Internship Task demonstrating the use of aggregate functions (SUM, AVG, MIN, MAX, COUNT) and grouping operations using the GROUP BY and HAVING clauses.

**Objective:**  
To summarize and analyze tabular data using SQL aggregate functions and grouping techniques.

**Overview:**  
Today's task focused on understanding and applying **aggregate functions**, **GROUP BY**, and **HAVING** clauses:  

- **Aggregate Functions:** Functions like `SUM`, `AVG`, `MIN`, `MAX`, and `COUNT` that calculate a single value from a set of rows.  
- **GROUP BY:** Allows categorizing data into groups based on one or more columns, enabling summary statistics for each group.  
- **HAVING:** Filters groups after aggregation, unlike `WHERE` which filters individual rows.

**What I Did:**  
- Used my existing `travellers` table to analyze numeric data such as budget, age, and days of trip.  
- Created a new **`payment`** table linked to the `travellers` table via `traveller_id` to track payments.  
- Applied aggregate functions to summarize data like total budget, average budget, average age of travellers, minimum and maximum trip duration, total successful payment amount and number of travellers.  
- Used `GROUP BY` to categorize travellers by payment date , destination.
- Used `HAVING` to filter groups based on aggregate values, such as destinations with high average destination budget. 
- Lernede how to connect tables and perform relational data analysis to get meaningful insights.

**Tools used:** MySQL Workbench
**Outcome:**  
- Gained hands-on experience in aggregation function and categorization.  
- Practiced **grouping and filtering** grouped data effectively.  
- Improved understanding of relational data analysis by linking two tables. 
