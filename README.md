# SQL-Data-Analysis

Project Overview:
The Coffee Chain Sales Analysis project was conducted to analyze the performance of a coffee chain across various U.S. locations using data from Kaggle. The dataset consisted of 1,063 records and 21 attributes related to sales performance, cost, and market conditions.

Tools and Techniques Used:

SQL & MySQL: Used for data manipulation and queries.
Normalization: Applied to structure the data into 3NF to eliminate redundancies and ensure data integrity.
Dimensional Modeling: Implemented to create a comprehensive schema that includes both Star and Snowflake schemas to support complex queries and efficient data retrieval.
Key Steps in the Analysis:

Data Loading and Normalization: Raw data was loaded into MySQL and normalized into relational tables that meet the third normal form (3NF), ensuring data integrity and reducing redundancy.
Schema Creation: Developed a dimensional model to organize data into a combination of fact and dimension tables, making it easier to perform analytical queries.
Fact Tables: Included key metrics like sales and targets.
Dimension Tables: Included product details, market information, and geographical data.
Analytical Queries and Reporting: Performed complex SQL queries to derive insights from the data. Key performance indicators (KPIs) such as total expenses, margins, sales, and profits were calculated.
Analyzed product and market performance, seasonal trends, and target achievements.
Examined the correlation between inventory margins and sales volumes, and compared state-level sales and expense data.
Outcomes and Insights:

Identified the most profitable and popular product lines and types.
Determined which states and markets are performing best in terms of sales and profits.
Provided recommendations for focusing on high-performing products and optimizing expenses in less profitable markets.
Challenges Faced:

Managing data redundancy and query complexity due to the comprehensive nature of the dimensional modeling.
Ensuring performance efficiency and maintaining the updated schema during the analysis.
Conclusions and Next Steps:
The project concluded with actionable insights into improving the coffee chain's profitability and market strategy. Recommendations were made to refine sales and marketing tactics based on the analysis. Future work includes a deeper dive into seasonal trends and inventory management to further optimize operations.
