# Coffee-shop-sales-analysis
This project is an individual task from Internpulse's data analytics track. It aims to analyze sales data from a coffee shop to identify trends, customer preferences, and areas for improvement. By examining sales patterns for various coffee types, identifying top-performing customers, comparing sales across different countries, and analyzing product demand, the project aims to provide valuable insights for enhancing the coffee shop's operations and decision-making.

# Tasks
1. Find trends of total sales (sales amount) for each coffee type.

2. Generate a table or chart highlighting the top 10 customers based on their contribution to total sales.

3. Find total sales by each country.
  
4. Find the total quantity ordered for each coffee type.

5. Add filtering options for roast type, loyalty card, year and size.
# Tools
Microsoft Excel
# Data Profiling
- The data coffee shop data contains three sheets: Order, Customers and Products
- The Order data contains 1000 rows and 5 columns, customer data contains 1000 rows and 9 columns, and the products data contains 48 rows and 7 columns.
- The common column between orders and customers data sheet is the Customer ID and the common column between the orders and products data sheet is the Product ID.

Some of the columns (Information) contained in the dataset include:
- Customer ID: Unique identifier for each customer
- Product ID: Unique identifier for each product
- Customer Name: Name of the customer
- Quantity: Quantity of coffee ordered/sold
- Coffee Type: Name of the coffee
- Size: Size in kilogram
- Order Date: Date of the order
- Roast type: L (Light), M (Medium), D (Dark)
- Country: Country of customer
- Coffee Type: Name of the coffee (e.g., Espresso, Latte, Cappuccino)
# Data Cleaning and Preparation
- Currency: I changed the "Unit price (USD)" data type from number to currency.
- Blank cells: no blank cell was found.
- New column: Added a column titled "Sales Amount" by multiplying the Unit Price(USD) x Quantity; this was created in order to know the total sales generated.
- VLOOKUP function: Used the function to retrieve information from the customers and products sheet using the customer ID and Product ID as lookup values. 
# Analysis
The analysis carried out include:
| Analysis | Details |
|---|---|
| Sales Trend Analysis | Utilized pivot table and chart to visualize sales trends for each coffee type over time. |
| Customer segmentation | Utlized pivot table and chart to identify the top customers based on their sales contribution. Applied a top N filter to identify the top customers.|
| Geographical analysis | Analyzed sales data by country inorder to identify the country with the highest sales volume.|
| Product Analysis | Analyzed the quantity ordered for each coffee type in order to identify the popular and less popular products. |
# Dashboard Development
Created an interactive dashboard using Excel's built-in tools. The dashboard included charts and filters to provide a comprehensive overview of the coffee shop's performance. Filters were implemented for roast type, loyalty card, year, and size to allow users to explore the data at different levels.

![image](https://github.com/user-attachments/assets/d2bfeede-7ce0-44f5-bd52-54f995c6800e)

# Result
- United states has the highest total sales generated from the sale of coffee.
- Allis Wilmore is the top customer with a spending amount of $317.07. The top 3 customers (Allis Wilmore, Brenn Dundredge, and Terri Farra) have spent significantly more than the rest of the customers.
- According to quantity ordered, Ara is the most ordered coffee type and lib is the least ordered coffee type across the analyzed countries.
- While Ara is the most ordered coffee for customers who prefer dark and medium roast type, Rob is the most ordered coffee for customers who prefer light roast type.
- The sales trend analysis showed that all coffee types exhibited significant fluctuations in sales over time. There were periods of high sales followed by periods of low sales. No particular coffee type dominated consistently throughout the period.

