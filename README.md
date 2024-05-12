**COFFEE CHAIN SALES DATA ANALYSIS**

**Project Overview:**
The Coffee Chain Sales Analysis project was conducted to analyze the performance of a coffee chain across various U.S. locations using data from Kaggle. The dataset consisted of 1,063 records and 21 attributes related to sales performance, cost, and market conditions.

**Tools and Techniques Used:**

**SQL & MySQL:** Used for data manipulation and queries.
**Normalization:** Applied to structure the data into 3NF to eliminate redundancies and ensure data integrity.
**Dimensional Modeling:** Implemented to create a comprehensive schema that includes both Star and Snowflake schemas to support complex queries and efficient data retrieval.

**Key Steps in the Analysis:**

**Data Loading and Normalization:** Raw data was loaded into MySQL and normalized into relational tables that meet the third normal form (3NF), ensuring data integrity and reducing redundancy.

**Schema Creation:** Developed a dimensional model to organize data into a combination of fact and dimension tables, making it easier to perform analytical queries.

**Fact Tables:** Included key metrics like sales and targets.

**Dimension Tables:** Included product details, market information, and geographical data.

**Analytical Queries and Reporting:** 
- Performed complex SQL queries to derive insights from the data. Key performance indicators (KPIs) such as total expenses, margins, sales, and profits were calculated.
- Analyzed product and market performance, seasonal trends, and target achievements.
- Examined the correlation between inventory margins and sales volumes, and compared state-level sales and expense data.

**Outcomes and Insights:**

**Profitable Product Lines:** Beans and Leaves are identified as the most profitable product lines. Focusing on these could maximize profit margins.

**State-Level Performance:** California is the leading state in terms of sales, while New York has the highest expenses. This suggests potential for optimizing operations and costs in New York.

**Target Sales & Profit Achievement:** Products like Lemon Tea and Darjeeling tea consistently exceed sales as well profit targets, indicating strong market demand and effective sales strategies for these items.

**Market Analysis:** Major markets contribute significantly to overall sales as compared to small markets.

**Expense Management:** The East and Central markets are more profitable compared to other regions, suggesting more efficient operations or lower costs.

**Year-on-Year Sales Trends:** Sales saw significant growth from 2012 to 2014, before a 20% drop in 2015, while inventory margins steadily increased each year which suggests improved profitability per product sold.






