FINANCIAL ANALYSIS OF FESTMAN STORES USING POWER BI, ETL, AND DAX FUNCTIONS
This project involves performing an in-depth financial analysis of FestMan Stores using Power BI. ETL processes were used to clean and transform the data, while advanced DAX functions enabled the extraction of key insights such as significant sales growth, profit trends, and regional performance. The analysis highlights both strong growth areas and potential opportunities for optimization.

Problem Statement
This project involves performing an in-depth financial analysis of FestMan Stores using Power BI. ETL processes were used to clean and transform the data, while advanced DAX functions enabled the extraction of key insights such as significant sales growth, profit trends, and regional performance. The analysis highlights both strong growth areas and potential opportunities for optimization.

Flow Of Project
ETL Process: Extracted data from raw sources, cleaned and transformed using Power BI for proper
visualization.

DAX Functions: Utilized DAX functions to calculate KPIs like sales growth, profit margins, and performance breakdown by region and segment.

Dashboard: Created an interactive Power BI dashboard to display financial insights, allowing for drill-downs into specific countries, segments, and product lines.

Data Source
The data used in this analysis consists of historical sales, profit, and discount data for FestMan Stores across different countries and market segments. The dataset includes columns such as: Sales Amount, Units Sold, Profit, Country, Segment Products,COGS,.

Visualization and Insights
Sales and Orders Growth
Sales: ₹9,23,11,095, a remarkable increase of 249.46% compared to the previous year’s ₹2,64,15,256. Orders: 861,132 orders, up by 225.36% from the previous year's 264,674 orders.

Conclusion: Both sales and order volume have seen explosive growth, indicating strong market demand and potential expansion in customer base.

Profit and Profit Margin
Profit: ₹1,30,15,238, a 235.58% increase from the previous year’s ₹38,78,465. Profit Margin: 14.1%, slightly down by 3.97% from last year’s 14.7%.

Conclusion: While overall profits have surged significantly, the decrease in profit margin may indicate rising costs or increased discounting strategies that need further analysis for optimization.

Orders and Profit Margin by Country
Top Countries by Orders: Canada (247K), France (241K), and the United States (233K) lead in order volume. Profit Margin by Country: Germany and France have the highest profit margins at 15.7% and 15.5% respectively. The United States has the lowest profit margin at 12.0%.

Conclusion: Germany and France are highly profitable markets, whereas the United States, despite strong order volume, shows lower profitability and may need attention for cost or pricing strategy improvements.

Discount Analysis (Discount Distribution)
High Discounts: 57.76% of orders received a high discount.

Medium Discounts: 32.62% of orders. Low Discounts: 9.62% of orders.

Conclusion: A significant portion of the orders benefited from high discounts, which could explain the slight dip in the profit margin despite a large sales increase. This raises the question of whether the discounts are sustainable or if adjustments are needed to improve profitability.

Profit Margin by Segment
Government: Most profitable segment, contributing ₹11M in profit.

Small Business and Channel Partners: Following behind with moderate profits.

Enterprise Segment: Shows a negative profit margin (-₹1M).

Conclusion: The Government sector is driving the majority of profits, while the Enterprise segment is underperforming and may require strategic intervention or cost realignment.

Top Products by Sales Top 3 Products
Paseo (₹33.01M), VTT (₹20.51M), Velo (₹18.25M)

Conclusion: Paseo is the best-selling product by a large margin, contributing significantly to sales performance. Continuing to push high-performing products could further boost sales.

Sales Trend Over Time
Sales Fluctuations: There’s a noticeable spike in sales during certain months in 2014, indicating periods of higher activity.

Conclusion: Identifying what drives these spikes can help plan future campaigns to capitalize on these peaks.Growth in sales and orders shows strong market expansion, but declining profit margins and heavy discounting may impact long-term sustainability. Regional and segment-specific analysis highlights areas of profitability and areas needing improvement, such as the Enterprise segment and United States market.

Usage
You can use this project to analyze historical financial data.

Create relationships among different financials matrices using the DAX functions.


SQL-Driven Booking Insights: From Data to Decisions
This project demonstrates the use of SQL to analyze booking data. The analysis includes creating views to retrieve specific insights, such as successful bookings, ride distances, customer behaviors, and payment trends. The project is structured around the creation of views to simplify complex queries and organize data effectively. The output is intended for business analysis and decision-making purposes.

Problem Statement
Analyzing booking data is critical for understanding customer behavior, ride trends, and operational inefficiencies. The goal of this project is to extract actionable insights from raw booking data by employing SQL for data extraction, preparation, and analysis. By creating organized views, we aim to simplify complex queries, enhance data accessibility, and support data-driven decision-making.

Dataset
The project uses a bookings table that contains information about rides, including:

Booking_ID: Unique identifier for each booking.

Customer_ID: Identifier for customers.

Booking_Status: Status of the booking (e.g., "Success," "Canceled by Customer").

Ride_Distance: Distance of the ride.

Vehicle_Type: Type of vehicle used for the ride.

Driver_Ratings: Rating given by customers to drivers.

Customer_Rating: Rating given by drivers to customers.

Payment_Method: Method used to make the payment (e.g., "UPI").

Booking_Value: Total value of the ride.

Incomplete_Rides: Flag indicating if the ride was incomplete.

Incomplete_Rides_Reason: Reason for incomplete rides (if applicable).

Canceled_Rides_by_Driver: Reason for cancellations by drivers.

Data Cleaning and Preparation
Removed duplicates to ensure data consistency.

Assigned correct data types to columns for accurate analysis.

Verified data integrity to handle null values and inconsistencies.

Tools Used
Database: MySQL

Query Editor: MySQL Workbench

Data Cleaning: Excel

Execution Steps
Set Up the Environment: Create a database and the bookings table.

Data Cleaning: Prepare the dataset by removing duplicates and assigning appropriate data types.

Run SQL Scripts: Execute the queries provided in the sql_queries.sql file to create views.

Validate Results: Use SELECT statements to verify the correctness of the views.

Repository Structure
README.md: This file containing project details.

Ola_Bookings.csv: Dataset used for the analysis.

sql_queries.sql: Contains all SQL queries used in the project.

Learning Outcomes
This project is a practical demonstration of how SQL can be used for data extraction, preparation, and analysis. It provides hands-on experience with:

Writing efficient SQL queries.

Using SQL views for simplifying and organizing complex queries.

Handling real-world data challenges through cleaning and preparation.

License
This project is licensed under the MIT License.
Create custom financial reports.

Gain insights into sales, profit margins, and discount strategies for other retail or financial datasets.



