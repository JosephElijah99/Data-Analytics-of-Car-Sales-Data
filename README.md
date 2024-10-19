Data Analytics Report: 
Car Sales Dataset

Dataset Overview
The dataset contains 157 rows and 16 columns.
The columns include manufacturer details, vehicle models, sales figures, resale values, vehicle types, prices, engine specifications, dimensions, and performance factors.

Data Quality Assessment
Some columns have missing values:
__year_resale_value: 36 missing values.
Price_in_thousands: 2 missing values.
Engine_size, Horsepower, Wheelbase, Width, Length, Curb_weight, Fuel_capacity, and Fuel_efficiency all have 1–3 missing values.
The data types of columns are generally appropriate; however, Latest_Launch should be converted to a datetime format for better analysis.

Descriptive Statistics and Insights
Sales Analysis:
The Sales_in_thousands column provides insights into vehicle sales, with a variety of models showing high or low sales figures.
Price and Resale Value:
Price_in_thousands and __year_resale_value help understand the price range and expected resale value, though incomplete data may need imputation or further investigation.
Performance Factors:
Columns like Horsepower and Power_perf_factor give information on vehicle performance.
Fuel Efficiency:
The Fuel_efficiency column provides fuel economy statistics, which are important for environmental and cost analysis.

Visualization Summary
The notebook uses Seaborn and Matplotlib for visualizing trends in sales, price, and performance factors. Such visualizations are crucial for identifying patterns and anomalies in the dataset.
