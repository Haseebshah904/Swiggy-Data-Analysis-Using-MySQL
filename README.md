# Swiggy Data Analysis Using MySQL

# Project Overview

This project involves an in-depth analysis of Swiggy’s customer, restaurant, and order data using MySQL to derive actionable insights. Swiggy is a popular food delivery platform, and understanding its data helps improve customer engagement, restaurant performance, and overall business growth.

By running various SQL queries, this analysis focuses on key areas such as customer behavior, restaurant performance, sales trends, and order preferences. The goal of this project is to provide data-driven recommendations for Swiggy's operations, marketing strategies, and partnerships.

# Objectives

+ Perform SQL-based analysis on Swiggy’s dataset to derive insights.
+ Answer critical business questions about customer engagement, sales, and restaurant performance.
+ Provide recommendations to enhance Swiggy’s service and operational efficiency.
  
# Dataset Description

The dataset used in this project consists of several tables related to Swiggy’s operations:
+ Users: Contains customer information such as customer IDs and other demographic details.
+ Restaurants: Information about restaurants listed on the Swiggy platform.
+ Food: Various food items offered by the restaurants.
+ Menu: Pricing details of food items across different restaurants.
+ Orders: Information about customer orders including amounts, dates, and ratings.
+ Delivery Partners: Details about the delivery partners.
+ Order Details: Specific items included in each order.
  
# SQL Queries and Business Insights

The analysis was conducted through several key SQL queries aimed at answering the following business questions:

## 1.Identifying Customers Who Have Never Ordered:

+ Query: A SQL query to identify inactive users.
+ Insight: Helps understand how many registered users have never placed an order, + which is useful for targeting these users with specific marketing campaigns.
  
## 2.Average Price per Dish:

+ Query: Averages the price of food items across different restaurants.
+ Insight: Guides pricing strategies by identifying average price ranges for popular dishes.
  
## 3.Top Restaurant by Number of Orders (for a Given Month):

+ Query: Identifies the most popular restaurant based on order count for a specific month.
+ Insight: Highlights top-performing restaurants, enabling Swiggy to focus marketing efforts.
  
## 4.Restaurants with Monthly Sales Greater Than a Specific Amount:

+ Query: Lists restaurants generating significant monthly revenue.
+ Insight: Helps Swiggy identify key restaurant partners for potential promotions and partnerships.
  
## 5.Order Details for a Specific Customer Within a Date Range:

+ Query: Retrieves all orders placed by a customer within a certain time frame.
+ Insight: Helps in personalizing marketing and improving customer service by understanding customer order history.
  
## 6.Restaurants with Maximum Repeated Customers:

+ Query: Identifies restaurants with a high rate of returning customers.
+ Insight: Highlights restaurants with strong customer loyalty, indicating high satisfaction.
  
## 7.Month-Over-Month Revenue Growth of Swiggy:

+ Query: Tracks Swiggy’s monthly revenue growth.
+ Insight: Crucial for understanding overall business performance and identifying revenue trends.
  
## 8.Customer Favorite Food:

+ Query: Identifies favorite food items of individual customers.
+ Insight: Useful for creating personalized recommendations and targeted marketing strategies.
  
## 9.Most Loyal Customers for All Restaurants:

+ Query: Finds the most loyal customers for each restaurant.
+ Insight: Assists in recognizing loyal customers, enabling Swiggy to implement reward programs.
  
## 10.Month-Over-Month Revenue Growth of a Specific Restaurant:

+ Query: Analyzes the revenue growth of individual restaurants over time.
+ Insight: Provides insights into the performance of specific restaurant partners, helping identify trends and seasonal patterns.
  
# Installation and Setup
To run the queries and replicate the analysis:
Clone the repository:

+ bash
+ Copy code
+ git clone https://github.com/yourusername/swiggy-data-analysis.git
  
## Import the SQL script:

+ The file SQL_Project.sql contains all the queries used for this analysis.
+ You can import this file into your MySQL database using the following command:

+ bash
+ Copy code
+ mysql -u username -p database_name < SQL_Project.sql
+ Ensure you have the required dataset and tables as per the description to run the queries successfully.

# Key Insights and Findings

+ Customer Behavior: Identifying inactive users and tracking customer preferences helps in designing targeted campaigns for customer retention.
+ Restaurant Performance: Analyzing top-performing restaurants and monthly sales trends enables Swiggy to optimize its restaurant partnerships and promotions.
+ Order Trends: Understanding favorite dishes and loyal customers allows Swiggy to personalize the user experience and improve customer satisfaction.
+ Revenue Growth: Month-over-month revenue analysis helps in tracking overall business performance and identifying opportunities for growth.
  
# Recommendations

Based on the analysis, the following recommendations are proposed:
+ Customer Engagement: Swiggy should focus on converting inactive users into active customers through targeted marketing campaigns.
+ Pricing Strategy: Use insights on average dish prices to optimize pricing strategies across different food items.
+ Loyalty Programs: Implement loyalty programs to reward repeat customers, increasing retention and satisfaction.
+ Restaurant Partnerships: Focus on promoting high-performing restaurants, while offering support to restaurants with high potential for growth.
+ Personalized Marketing: Leverage customer order histories and favorite food items to deliver personalized recommendations and offers.
  
# Conclusion

This project provided key insights into Swiggy’s customer engagement, restaurant performance, and order trends using MySQL-based data analysis. The results of this project can guide Swiggy in improving its operational efficiency, customer satisfaction, and overall business growth through data-driven decision-making.
