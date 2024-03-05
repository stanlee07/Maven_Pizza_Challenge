# MAVEN PIZZA CHALLENGE

![image](https://github.com/stanlee07/maven_pizza_challenge/assets/41926231/23c40d68-7ffd-4db7-ad0e-a5276ec866f0)


## Table of Contents
- [Project Overview](#project-overview)
- [Project Objective](#project-objective)
- [Data Sources](#data-sources)
- [Data Preprocessing](#data-preprocessing)
- [Data Analysis](#data-analysis)
- [Data Visualisation](#data-visualisation)
- [Key Insights](#key-insights)
- [Recommendation](#recommendation)

## Project Overview
The "Maven Pizza Challenge" is a challenge that was hosted by maven analytics. The purpose of the challenge was for the participants to play the role of a BI Consultant hired by Plato’s Pizza, a Greek-inspired pizza place in New Jersey and give an in-depth analysis of the transactional data that they provided.

Challenge URL: https://www.mavenanalytics.io/blog/maven-pizza-challenge

## Project Objective
This objective of this challenge is to the data and put together a report to help the company find opportunities to drive more sales and work more efficiently. The company would also like the report to answer the following questions:
- What days and times do we tend to be busiest?
- How many pizzas are we making during peak periods?
- What are our best and worst selling pizzas?
- What's our average order value?
- How well are we utilizing our seating capacity? (we have 15 tables and 60 seats)


## Data Sources
The dataset used in this challenge provided by Maven Analytics is a 1-year transactional data for Plato's Pizza, and it containted four (4) separate CSV files (Orders, Order Details, Pizzas and Pizza Types). These tables have been explained below:
- **Orders:** contains the date & time that all table orders were placed.
- **Order Details:** contains the different pizzas served with each order in the Orders table and their quantities.
- **Pizzas:** contains the size and price for each distinct pizza in the Order Details table, as well as its broader pizza type.
- **Pizza Types:** contains details on the pizza types in the Pizzas table, including their name as it appears on the menu, the category it falls under, and its list of ingredients.


## Data Preprocessing
The data was loaded and transformed using the Power Query Editor in Microsoft Power BI. In the preprocessing phase, the tables were connected together to create a snowflake schema with the Orders table as the core fact table and others as the dimensional tables. From the orders table, dates and time tables were generated to enable deeper analysis into the times and days of orders. 

## Data Analysis
I thoroughly examined the given dataset, applying relevant statistical methods to extract meaningful insights. My objective was to reveal concealed patterns and correlations that illuminate the distinctive dynamics among these indicators across various pizza orders.

## Data Visualization
A single page report was created which visualized the key insights generated from the analysis 

## Key Insights
- The restaurant offered 32 types of pizza which could be grouped into 4 major categories based on the ingredients of the pizza as well as 5 categories based on the size of the pizza.
- The most preferred pizza type is the Classic Pizza and the least preferred is the Brie Pizza.
- The total orders had in the 1-year period is 21,350 and the average price of each order was $38.
- The busiest day is Friday, while Sunday recorded the least sales.
- Peak times are between 12.30 and 13.20.
- The sitting capacity exceeeds the limit during the peak times (12pm - 1pm) on weekdays.
- The highest sale day is November 27 which is Black Friday.


## Recommendation
- To eradicate waste and promote the sale of the least ordered pizza, a pair sale would be advised.
- To decongest teh peak time, customers can be adviced to place their orders ahead, and come pick up when it is ready.
- Spreading the sitting arrangements to sitting orders like 2:1 and 6:1 can free up space for couples or groups that wisht to eat in.
- Promotions and discounts can also help to increase sales on Sunday.
