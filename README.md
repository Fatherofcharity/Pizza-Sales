# Power BI Dashboard of Pizza Place Sales

This repository contains a Power BI dashboard that I created using the Pizza Place Sales dataset from Kaggle. The dataset contains sales data for a pizza chain with multiple locations. I performed some data cleaning and transformation to prepare the data for analysis. I also used DAX calculations to get the sum of revenue of $818k. The dashboard shows the sales performance of different pizza types, categories, locations, and time periods.

## Data Source

The data source for this dashboard is the from Kaggle. It consists of two tables: Sales and Menu. The Sales table has 14 columns and 5,000 rows. It contains information such as order date, location, quantity, and revenue. The Menu table has 5 columns and 50 rows. It contains information such as pizza type, category, size, and price.

## Data Preparation

I used Power Query Editor in Power BI Desktop to clean and transform the data. Some of the steps I took include:

- Renaming and reordering the columns for clarity and consistency
- Changing the data types and formats of some columns
- Removing duplicates and null values
- Splitting the OrderDate column into Year, Month, and Day columns
- Creating a Calendar table to enable date filtering and grouping
- Merging the Sales and Menu tables based on the PizzaType column
- Creating a Star schema with Sales as the fact table and the other tables as dimension tables

## Data Analysis

I used Power BI Desktop to create various visuals and measures to analyze the data. Some of the measures I created using DAX are:

- Revenue 
- Quantity 
- Average Revenue per Order 
- Average Quantity per Order 

Some of the visuals I created are:

- A donut chart showing the revenue by category
- A clustered column chart showing the top 5 and bottom 5 pizza types by revenue
- A line and clustered column chart showing the trend of monthly sales by revenue and quantity
- A card showing the total revenue
- A slicer to filter the data by date range

## Dashboard Preview

Here is a screenshot of the dashboard:

![Pizza Sales](https://github.com/Fatherofcharity/Pizza-Sales/assets/135114403/affdc6f2-bdf8-44fd-b14d-c27ac8f6f42a)


You can also view the interactive dashboard [here]

## How to Use

To use this dashboard, you need to have Power BI Desktop and Power BI service accounts. You can download the Power BI Desktop file (.pbix) from this repository and open it in Power BI Desktop. You can then publish the file to Power BI service and create a dashboard from the report. Alternatively, you can import the file directly to Power BI service and create a dashboard from there.

## Contact Me

If you have any questions, feedback, or suggestions for this dashboard, please feel free to contact me. You can also check out my other Power BI projects on my GitHub profile. Thank you for your interest and support!
