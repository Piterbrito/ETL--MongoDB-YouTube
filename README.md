# ETL--SQL-database-YouTube. 
Project 2

# Background

Project ETL (Load, Transform and Load), three database functions that are combined into one tool to pull data out of one database and place it into another database.

Extract is the process of reading data from a database. In this stage, the data is collected, often from multiple and different types of sources.

Transform is the process of converting the extracted data from its previous form into the form it needs to be in so that it can be placed into another database. Transformation occurs by using rules or lookup tables or by combining the data with other data.

Load is the process of writing the data into the target database.

# Goal

Get Youtube data from diferent variaty of source such APIs, Web-scraping and Google-Scholar data-sets 

Get a Large amount of data with diferent formats such (csv, xml, json, raw), goal is to get 25 files with around 1 Million rows.

Once I have identified the datasets,I will perform ETL on the data and document the following within the jpynb.

The type of transformation needed for this data (cleaning, joining, filtering, aggregating, etc).

The type of final production database to load the data into (relational or non-relational).

The final tables or collections that will be used in the production database.

Submit a final technical report with the above information and steps required to reproduce your ETL process.



# Thinking Process 

Extract the data from a reliable data source like Kaggle, Web-scraping and API.
bring it into the python environment with pandas as a csv and structure it into a pandas dataframe to begin the transformation phase of the data by cleaning the data, fixing the null and missing values , grouping by relevant variables to create visualizations and identify  trends and variables. After the data is cleaned and fixed i will load the pandas dataframe into a local database such as postgreSQL and check for SQL tables with SQL commands.


# Report

I will included a detailed data dictionary along with the code and the corresponding output of each cell step by step that will cover the detailed explanantion of taking that particular approach towards solving the problem.
