# Crowdfunding_ETL

We completed a mini-project focused on extract, transform, load (ETL) concepts. The data was focused on crowdfunding data of successful or not successful launches of small businesses or project. 

For the category and subcategory dataframes, the team extracted and transformed the crowdfunding.xlsx file to create category_ids and subcategory_ids. For the campaign dataframe, the team extracted and transformed the crowdfunding.xlsx file to create a dataframe that ultimately merged all 3 dataframes (category, subcategory, and campaign). All three dataframes were exported to csv files to later be imported into PostgreSQL for querying.


For the Contacts dataframe, we chose to do Option 1 to transform the data using Pandas instead of regex.  In order to split the first name and last name I looked on Saturncloud.io to find an example on how to split the string and set it to two separate columns.  We also used the QuickDBD tool to create the ERD and schema for the crowdfunding database.
