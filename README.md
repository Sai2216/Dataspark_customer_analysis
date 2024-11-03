# Dataspark_customer_analysis
DataSpark: Illuminating Insights for Global Electronics

Project Overview
This project entails a structured process of cleaning, merging, and analyzing customer, sales, exchange rate, and store data. Below is a step-by-step guide to the workflow:

Step 0: File Collection

Create a folder containing all the CSV files required for the project. Place the Python script in the same folder for seamless execution.

Step 1: Data Cleaning

Reading the Data: Used Python and Pandas to import CSV files for customer, sales, exchange rate, and store data.
Handling Missing Values: Detected and filled missing values as needed using appropriate methods.
Data Type Conversion: Standardized columns to their correct data types (e.g., dates, integers, floats).

Step 2: Data Merging

Merging Datasets: Combined all cleaned datasets into a single DataFrame using the Pandas merge function with an inner join.

Step 3: Uploading Data to SQL

Connecting to SQL Database: Established a database connection via SQLAlchemy.
Pushing Data to SQL: Uploaded the cleaned and merged DataFrame into the SQL database named capstone.

Step 4: Data Analysis with SQL

Writing SQL Queries: Developed SQL queries to analyze customer, sales, product, and store data.

Step 5: Data Visualization with Power BI

Uploading Query Results: Imported SQL query results into Power BI.
Creating Visualizations: Developed visualizations to effectively present insights derived from the analysis.
