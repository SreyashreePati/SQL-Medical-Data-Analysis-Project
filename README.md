# SQL-Medical-Data-Analysis-Project
This SQL project is designed to analyze a medical dataset containing information about ladies' health parameters, including age, blood pressure, pregnancy status, drug reactions, and anxiety levels.
The queries focus on data filtering, aggregation, modification, and categorization to extract meaningful insights.

1. Data Optimization & Schema Management
Added an index on the ‘Name’ column for faster search queries.
Described the table schema to understand data structure.
2. Statistical Analysis
Calculated the average, minimum, and maximum age of all individuals.
Computed the average age of pregnant vs. non-pregnant individuals.
Determined the average blood pressure of those who had a drug reaction vs. those who didn’t.
3. Data Categorization & Modification
Created a new column ‘Age_Group’ and categorized individuals as:
Low (16-21 years)
Middle (22-34 years)
High (35+ years)
Updated specific records:
Changed Reetika’s age to 32.
Renamed Reena to Shara.
Removed the ‘Chlstrl’ column from the dataset.
4. Data Filtering Based on Attributes
Selected only Name, Age, and Blood Pressure for a simplified view.
Filtered individuals based on name patterns:
Names starting with ‘E’, ‘A’, ‘K’.
Names ending with ‘i’ or ‘a’.
Names containing ‘a’ anywhere.
Identified individuals based on health conditions:
Low Age Group (16-21 years).
High Age Group (35+ years).
Pregnant women whose names start with ‘A’.
Blood Pressure > 120 (potential hypertension cases).
Blood Pressure between 100-120 (borderline cases).
Low anxiety levels and age < 30 (possibly healthier individuals).
5. Data Sorting & Ordering
Sorted individuals in ascending order based on BP to identify those with the lowest pressure.
Sorted individuals in descending order based on Age to list the oldest first.
Project Purpose & Learning Outcomes
This project demonstrates the ability to:
Optimize database performance using indexing.
Retrieve and analyze health-related data efficiently.
Use SQL functions to compute averages, minimum, and maximum values.
Apply filtering conditions to extract specific data subsets.
Modify and categorize data dynamically using CASE statements.
Sort and organize data for better visualization and reporting.
