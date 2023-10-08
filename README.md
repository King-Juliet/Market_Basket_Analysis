# MARKET BASKET ANALYSIS
This project aims to use the data provided a store owner to identify customer purchasing habits to enable the discovery of items frequently purchased together to facilitate the development of combo deals and recommendations of items to buy to both new and existing customers, thereby cross-selling items in the store to generate more revenue and improve customers satisfaction and experience.
Market basket analysis is very useful in cross-selling products. This project focuses on using Apriori algorithm to perform market basket analysis to facilitate cross-selling of products in order to increase revenue.
For this project:
Jupyter notebook was used as the IDE to facilitate detailed and easy understanding of the workflow of the project to both technical and non-technical users.
Pandas library was used to power the data importation, data cleaning, data manipulation, data wrangling and feature engineering aspect of the project.
Apriori algorithm was used for market basket analysis.
# STEPS:
After importation of the all the required libraries into the working directory, the data was then read into Pandas DataFrame for data procecessing and analysis to derive insights.
The data processing steps carried out was done to ensure the data was in the right format for analysis to derive reliable insights for business decision making. The steps taken include; data cleaning to remove dirty data, data type conversion into the appropriate format, column name renaming for better aesthetics, datetime handling to enable trend analysis.
After processing the data, exploratory data analysis was carried out to gain insights on sales trends, product performance and items frequently purchased together. 
# FINDINGS/CONCLUSION
After data analysis was carried out, it was discovered that within the 2 year span of the data provided, there was a 16.6% decrease in sales, which after further analysis was linked to the 0.2% decrease in the number of items ordered. The most ordered item from the store was Traditional Baguette and it received its most orders on Sunday. Since Traditional Baguette was the most frequently ordered item from the store, market basket analysis was carried to discover items that can be sold together with it to facilitate the business decision of combo-deal sales on Sundays (cross-selling). 
After performing the market basket analysis, it was discovered that the top items frequently bought together with Traditional Baguette include boule 400g, Complet, Moisson, Coupe and Vik bread. 
In addition to cross-selling the most sold items to items it was frequently bought with, other frequently bought combination of items can also be bought. 
The combo-deal sales is aimed at increasing the number of orders made, thereby increasing sales.


