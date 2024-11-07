# Power BI Retail Dashboard Exercise
This repository contains a Power BI project designed to build a retail analytics dashboard by integrating and analyzing multiple data sources. The aim is to create insightful visualizations for business decision-making, leveraging DAX and Power BI’s data modeling features.

Project Overview
The goal of this exercise is to manage data from multiple sources and define relationships across tables to enable an analytical dashboard. The dashboard provides insights such as total revenue, weekly and monthly trends, customer behavior, and product performance across various dimensions like city and zone.

Business Context
In this exercise, you are tasked with analyzing retail data from four distinct files. The data covers various aspects of retail performance, such as sales, returns, and geographic segmentation. By defining relationships and creating calculated fields, you’ll produce a comprehensive view of business performance.

Key Tasks
Data Loading:

Import four data tables into Power BI, ensuring headers align with field names.
Data Cleaning:

Remove records where fields such as Zone and CityTier are missing.
Create relationships between common fields across tables (e.g., linking City in Mod3_Raw_CityTier_v01 with City in PinCode-Geo).
Data Transformation:

Create a new column Net_Units in the sales table to calculate units sold after cancellations.
Rename City to City_Old and add a new City column containing only the city name.
Add OrderDayOfWeek for weekday analysis and OrderWeekStart to view weekly trends.
Dashboard Creation:

Develop visualizations to display metrics like:
Total Revenue: Visualize total revenue over time and across dimensions.
Total Quantity and Cancellations: Analyze quantity sold and cancellations by time, product, and geography.
Customer and Transaction Analysis: Break down the number of customers and transactions by month, week, day, product group, city, zone, and city tier.
Dashboard Finalization:

Build a high-level dashboard combining all analyses, with filters to view specific segments.
Technologies Used
Power BI: For data modeling, transformation, and visualization.
DAX (Data Analysis Expressions): To create calculated fields for custom insights.

Results
This project delivers a Power BI dashboard providing an in-depth look at retail performance by various dimensions, useful for identifying trends and making data-driven decisions.

Contributing
Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request.

