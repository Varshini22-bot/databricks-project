# databricks-project
🔹 Project Overview

This project demonstrates data analysis using SQL on the Netflix dataset in Databricks. It focuses on extracting meaningful insights such as content distribution, trends over time, and ratings analysis.

🔹 Tools & Technologies Used
Databricks (SQL Editor)
GitHub (for version control)

🔹 Dataset Description
The dataset contains information about Netflix titles, including:
Title
Type (Movie / TV Show)
Release Year
Duration
Rating
Date Added
Description

🔹 Project Structure
databricks-netflix-analysis/
│── queries.sql        # All SQL queries
│── report.md          # Detailed report with explanations
│── screenshots/       # Output screenshots from Databricks
│── README.md          # Project documentation
🔹 Steps Performed
Uploaded dataset into Databricks
Created table using SQL
Loaded dataset into table
Performed SQL queries for analysis
Captured output screenshots
Documented results and explanations
Uploaded project to GitHub

🔹 Key SQL Queries
✔ Basic Queries
Display all records
Count total entries
Filter Movies and TV Shows
✔ Aggregation
Count content by type
Count by rating
Top release years
✔ Advanced Queries
Window functions (RANK, ROW_NUMBER)
Running totals
Subqueries
CASE statements

🔹 Sample Query
SELECT type, COUNT(*) AS total
FROM netflix_titles
GROUP BY type;

🔹 Key Insights
Netflix has a mix of Movies and TV Shows
Content production increased over recent years
Certain ratings dominate the dataset
Trends can be analyzed using SQL queries
🔹 Conclusion

This project highlights how Databricks and SQL can be used for efficient big data analysis. It demonstrates important SQL concepts such as aggregation, filtering, window functions, and data transformation.

🔹 databricks Link
https://dbc-91d26094-d981.cloud.databricks.com/explore/data/workspace/default/netflix_titles?o=7474653407878634

(Add your repository link here)
