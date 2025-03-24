# Project-2
files are in answers and etl jupyter file

Crowdfunding ETL Project
This project demonstrates the complete Extract, Transform, Load (ETL) process for a fictional crowdfunding campaign database using Python, Pandas, PostgreSQL, and data modeling tools.

Technologies Used
Python (Pandas)

Jupyter Notebook

PostgreSQL & pgAdmin

QuickDBD (for ERD creation)

Git & GitHub

Files Included
category.csv

subcategory.csv

contacts.csv

campaign.csv

crowdfunding_db_schema.sql – PostgreSQL schema file

ETL_Mini_Project_Starter_Code.ipynb – ETL process notebook

ERD Screenshot

ETL Steps
Extract data from Excel files (crowdfunding.xlsx, contacts.xlsx)

Transform and clean:

Normalize category/subcategory tables

Parse contact info from JSON strings

Format dates and numeric values

Load cleaned data into a PostgreSQL database

Verify table creation and data integrity using SQL SELECT statements

ERD Diagram in answers file

Setup
To run the project locally:

Clone this repo

Import crowdfunding_db_schema.sql into PostgreSQL

Import each CSV into its corresponding table

Run SQL queries to verify the data
