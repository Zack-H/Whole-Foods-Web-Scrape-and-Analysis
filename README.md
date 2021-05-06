# Project Name
Analyzing Whole Foods Weekly Deals

# Project Objective
Scrape data about Whole Foods' weekly deals to gain inights as to the discounts places on each product and category


# Job Description
Uber Cornershop is an on-demand grocery delivery platform that has been highly successful internaitonally and has recently enter the United States. It will compete with companies like Amazon Fresh and Instacart, who have also ready been in the the United States market for some time.
This job is for a Data Analyst position, who will work with data to shape the strategic future of the comapny. Cornershop relies on data for decision making, and therefore needs skilled analysts to gather and utilze data. Cornershop request as lesat 4 years of SQL experience as well as scripting experience.

This project is an example of what work might be done by a data analyst at Cornershop. This project generates a dataset with inforamtion pertainent to Cornershop's that can be queried to extract specfic details ro to answer speicific business questions.


# Data
The data for this project came directly from Whole Foods website (https://www.wholefoodsmarket.com/products/all-products). 
By passing in parameters to retrieve only items on sale and for a specific store, I retrieved only the items on sale at my local store as opssed to all items for sale.
Since the dataset was limited to only items on sale at one store for one week, there were a limited number of results. Additionally, not all items had a sale price and prime price, since not all items offer an extra discount to Prime members.


# Notebooks
Data collection: https://github.com/Zack-H/sql-2021/blob/main/data_collection.ipynb

Data analysis: https://github.com/Zack-H/sql-2021/blob/main/sql_analysis.ipynb


# Future Improvements
1. Since these deals update on a weekly basis, it would better to add a database column with the data the data was scraped on, then repeat the scrape each week. This would allow the dataset to build up over time, offering more insights, while still allowing the analyst to segment data on a per-week basis
2. Currently, if a new product is added, the user must manually execute SQL to normalize the data. This could presetn problems if the previous imporovement is implemented. Also, if a new seller or category is added, then those tables mus tbe manually updated as well. It would better to take care of this automatically in the scrape (possibly by placing data in different dictionaries for each table, then uploading several tables instead of just the one)
