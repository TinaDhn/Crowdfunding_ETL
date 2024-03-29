Crowdfunding_ETL
Introduction
ETL (Extract, Transform & Load) is a foundational skill. In the real world, data is everywhere and often scattered across multiple sources, and it can be messy. Understanding how to extract, load, and transform data is a critical concept as it enables you to have clean, up-to-date, and accurate data. It empowers you to become an expert in your data by allowing you to manipulate data types, fix formatting issues, and create additional columns to enrich and gain meaningful insights from your data. In this project, I will be using the data below to perform extraction, transformation, and loading of the data.


Tools and Technologies Used
Jupyter Notebook
Pandas
NumPy
SQL Database
Quick Database Diagrams for Entity Relationship Diagram (ERD)

Data Analysis Process
Extraction: Data was extracted from the crowdfunding database using SQL queries.
Transformation: The data was cleaned and transformed using Pandas and NumPy in a Jupyter Notebook environment.
Loading: Cleaned data was stored and managed in an SQL database for further analysis.
Visualization: Visualizations, including Entity Relationship Diagrams (ERD), were created to provide a clear representation of the data structure and relationships.
Analysis: Various metrics such as crowdfunding success rates, pledged amounts, and geographic distribution were analyzed to identify trends and patterns.

Sources of data
Within Resources Folder:
contacts.xlsx
crowdfunding.xlsx
Database Type for Final Production Environment
Description: The proposal includes specifying the type of database that will be used for the final production environment to store and manage the data.



Create the Category and Subcategory DataFrames:
Import crowdfunding.xlsx  and create category and subcategory Dataframe  and export in csv files to Export folder
Create the Campaign DataFrame:
Import and transform the crowdfunding.xlsx Excel data to  a campaign DataFrame and clean the data frame using pandas and export to csv file Export folder

Create the Contacts DataFrame
Import and transform the contacts.xlsx Excel data to  a campaign DataFrame and clean the data frame using pandas and export to contacts.csv file Export folder

Crowdfunding data utilizes the Extraction, Transformation, and Loading (ETL) methodology to accurately study the data. This technique allows you to clean the data, compartmentalize it appropriately in the columns for easier visual of the data, and allows you to perform an analysis quickly. I used Jupyter notebook along with Pandas, numpy, and also utilized SQL database to load the data and then store and manage it. Finally, I made the Entity Relationship Diagram (ERD) to provide a visual representation by using "Quick Database Diagrams" website. Looking at the data, it can be noted that the Theater category has the highest rate and Journalism and Games had the lowers rate. The Theater categoy also had the highest pledged amounts which were higher than $15 million. Categories such as Film and Video, Music, Publishing, and Technology also rated higher than Journalism and Games. It can also be noted that United States, Canada, and UK had the highest sum of pledged amounts to support crowdfunding in their countries compared to other countries.

