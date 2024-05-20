# Home_Sales
Result : 
# ***The cached runtime is 0.33 seconds and the uncached runtime is 0.57 seconds. By comparing the runtime of the code with and without caching, we can see the potential performance improvement gained from caching.***

# ***The parquet runtime is 0.44 seconds and the cached runtime is 0.33 seconds. The time it takes to read data from a Parquet file is slightly higher than cached runtime.***

# ***Enabling caching resulted in a notable improvement in runtime compared to the uncached version and parquet version of the code***

# Instructions
Renamed the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

Imported the necessary PySpark SQL functions for this assignment.

Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

Created a temporary table called home_sales.

Answered the following questions using SparkSQL:

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

Cached your temporary table home_sales.

Checked if your temporary table is cached.

Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

Partition by the "date_built" field on the formatted parquet home sales data.

Created a temporary table for the parquet data.

Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

Uncached the home_sales temporary table.

Verify that the home_sales temporary table is uncached using PySpark.

Downloaded your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.

Support and Resources
