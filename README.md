![WalmartLogo](https://github.com/Nish-gopi/Walmart-Sales-Data-Analysis-SQL-Excel-/assets/92908009/60eeb5b5-25cf-4f3f-835a-9aea66d9e9c0)
**Walmart Sales Data Analysis SQL Project**

**About**
In this project, we delve into Walmart's sales data to uncover valuable insights that can inform strategic decisions and optimize sales operations. By analyzing sales patterns, identifying top-performing branches and products, and understanding customer behavior, we aim to enhance Walmart's sales strategies. The dataset utilized in this project is sourced from the Kaggle Walmart Sales Forecasting Competition.

**Purpose of the Project**
The primary objective is to gain actionable insights from Walmart's sales data to drive business growth and efficiency. By exploring various factors influencing sales across different branches, we seek to uncover opportunities for improvement and optimization.

**Leveraging SQL for Analysis**
SQL (Structured Query Language) is a powerful tool for analyzing structured data stored in databases. By using SQL in this project, we can efficiently query, manipulate, and analyze the Walmart sales data to derive meaningful insights. SQL offers a wide range of functions and capabilities, making it ideal for tasks such as data wrangling, feature engineering, and exploratory data analysis.

**About the Data**
The dataset comprises sales transactions from three Walmart branches located in Mandalay, Yangon, and Naypyitaw. It contains detailed information about each transaction, including invoice ID, branch, city, customer type, product line, unit price, quantity sold, VAT, total cost, date, time, payment method, cost of goods sold (COGS), gross margin percentage, gross income, and rating.

**Analysis List**

**Product Analysis**
1.Perform in-depth analysis on different product lines. 2.Identify top-performing product lines based on sales and profitability. 3.Identify areas for improvement in underperforming product lines.

**Sales Analysis**
1.Analyze sales trends over time to identify patterns and anomalies. 2.valuate the effectiveness of sales strategies implemented across branches. 3.Determine factors contributing to fluctuations in sales and revenue.

**Customer Analysis**
Segment customers based on their purchasing behavior and preferences. Analyze customer demographics to understand their impact on sales. Evaluate the profitability of different customer segments and identify opportunities for targeted marketing.

**Approach Used**
**Data Wrangling:**
Identify and handle missing or null values in the dataset. Prepare the data for analysis by ensuring data consistency and integrity. Feature Engineering:

Create new features such as time_of_day, day_name, and month_name to provide additional insights into sales patterns and trends. Transform and preprocess data to extract meaningful information for analysis.

**Exploratory Data Analysis (EDA):**
Product
How many unique product lines does the data have? What is the most common payment method? What is the most selling product line? What is the total revenue by month? What month had the largest COGS? What product line had the largest revenue? What is the city with the largest revenue? What product line had the largest VAT? Fetch each product line and add a column to those product line showing "Good", "Bad". Good if its greater than average sales Which branch sold more products than average product sold? What is the most common product line by gender? What is the average rating of each product line?

Sales
Number of sales made in each time of the day per weekday Which of the customer types brings the most revenue? Which city has the largest tax percent/ VAT (Value Added Tax)? Which customer type pays the most in VAT?

Customer
How many unique customer types does the data have? How many unique payment methods does the data have? What is the most common customer type? Which customer type buys the most? What is the gender of most of the customers? What is the gender distribution per branch? Which time of the day do customers give most ratings? Which time of the day do customers give most ratings per branch? Which day fo the week has the best avg ratings? Which day of the week has the best average ratings per branch?

**Revenue And Profit Calculations**
$ COGS = unitsPrice * quantity $

$ VAT = 5% * COGS $

is added to the and this is what is billed to the customer.

$ total(gross_sales) = VAT + COGS $

$ grossProfit(grossIncome) = total(gross_sales) - COGS $

Gross Margin is gross profit expressed in percentage of the total(gross profit/revenue)

$ \text{Gross Margin} = \frac{\text{gross income}}{\text{total revenue}} $

Example with the first row in our DB:

**Data given:**

$ \text{Unite Price} = 45.79 $ $ \text{Quantity} = 7 $ $ COGS = 45.79 * 7 = 320.53 $

$ \text{VAT} = 5% * COGS= 5% 320.53 = 16.0265 $

$ total = VAT + COGS= 16.0265 + 320.53 =

$ \text{Gross Margin Percentage} = \frac{\text{gross income}}{\text{total revenue}}=\frac{16.0265}{336.5565} = 0.047619\approx 4.7619% $

**Conclusion**
Through comprehensive analysis of Walmart's sales data using SQL, we aim to provide actionable insights that can drive business growth and improve operational efficiency. By leveraging SQL's capabilities for data analysis, we can unlock valuable insights from the dataset, empowering Walmart to make informed decisions and optimize its sales strategies for greater success.
