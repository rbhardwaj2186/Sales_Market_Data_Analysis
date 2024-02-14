# Sales Analysis and Visualization






Exploring Sales Market Data for Analysis



 This project involves analyzing and visualizing sales data using Python libraries such as Pandas, NumPy, and Matplotlib. The key steps and insights are outlined below:

![Sales-data-analysis-for-sales-managers](https://github.com/rbhardwaj2186/Sales_Market_Data_Analysis/assets/143745073/6d675666-ede9-43f1-9c86-6860c3851e09)


     Data Loading and Cleaning:

        The sales data is loaded from a Feather format file into a Pandas DataFrame named 'all_data.'
        Null values are initially checked and subsequently removed using the dropna method.
        Duplicated instances are identified, examined, and then dropped from the dataset.

    Feature Engineering - Extracting Month:
        The 'Order Date' column is utilized to extract the month information, resulting in the creation of a new 'Month' column.
        An alternative approach using a function named 'return_month' is also demonstrated.

    Data Type Conversion:
        Data types are appropriately converted, with the 'Quantity Ordered' column transformed to integer type and the 'Price Each' column to float type.

    Sales Analysis:
        A new 'sales' column is created by multiplying 'Quantity Ordered' with 'Price Each.'
        Monthly sales are calculated by grouping the data by the 'Month' column and summing the 'sales' column.
        A bar plot is generated to visualize total sales for each month.

    City-wise Analysis:
        The 'Purchase Address' column is used to extract the city names, creating a new 'city' column.
        A pie chart is created to illustrate the distribution of orders among different cities.

    Product Sales Analysis:
        A DataFrame named 'count_df' is formed by grouping the data by the 'Product' column and aggregating 'Quantity Ordered' and 'Price Each.'
        A bar chart and line plot are combined to visualize the total quantity ordered and average price for each product.

    Conclusion and Interpretation:
        The analysis concludes with insights such as the best month for sales and the top-selling product being AAA Batteries (4-pack). A correlation between product price and quantity ordered is suggested.

    Additional Notes:
        The project includes steps to handle warnings, convert data types, and perform various data cleaning and analysis tasks.

        Overall, this project provides a comprehensive exploration of sales data, offering valuable insights through visualizations and analysis.

