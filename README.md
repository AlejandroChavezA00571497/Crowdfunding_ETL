# Crowdfunding_ETL
Project 2 for the Tec de Monterrey Data Analysis Bootcamp, Team 04

Jupyter Notebook file that extracts information from .xlsx files, analyzes it, updates it, and exports .csv files.

ETL_Mini_Project_EEsquivel_AChavez.ipynb is the main file, it uses pandas, numpy, pprint and json in order to split information from columns, iterating and using the .split() method to take information from the crowdfunding.xlsx file and output 2 different .csv files, one for categories and another for subcategories. Datatypes from columns in the same crowdfunding.xlsx file are converted and merged with the created .csv files in order to arrive at a cleaned DataFrame, which is exported into a campaign.csv file.

From the contacts.xlsx we create a Pandas DataFrame, using iteration to extract data and Pandas methods to update the DataFrame and output a contacts.csv file. We also explore a method to achieve the same result using regex.

As well as the .ipynb file, there's also a .sql file, Crowdfunding_ETL_SQL_Schema.sql, where we define the table schema for passing the 4 .csv files previously created into SQL tables, based on the ERD shown in Crowdfunding_ETL_SQL_Schema_ERD.png.

The main files for this project, ETL_Mini_Project_EEsquivel_AChavez.ipynb, Crowdfunding_ETL_SQL_Schema.sql and Crowdfunding_ETL_SQL_Schema_ERD.png exist within the main directory. In the main directory there're also the Resources directory, where the contacts.xlsx and crowdfunding.xlsx files are. The Outputs directory is also in the main directory, and it contains the 4 .csv files, campaign.csv, category.csv, contacts.csv and subcategory.csv, as well as screenshots serving as evidence of the SQL tables creation and querying of data.

Contributions:
- Data Analysis Bootcamp Classes
- https://pandas.pydata.org/docs/user_guide/dsintro.html#dataframe
- https://www.w3schools.com/python/python_regex.asp
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.str.split.html
- https://www.w3schools.com/sql/
