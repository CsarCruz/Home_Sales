# Home Sales Project

In this project, SparkSQL is used to determine key metrics about home sales data. Spark is utilized to create temporary views, partition the data, cache and uncache a temporary table, as well as verify that the table has been uncached.


## Process

1. Import the PySpark SQL functions.

2. Read the home_sales_revised.csv data into a Spark DataFrame.

3. Create a temporary table called home_sales.

4. Use SparkSQL for solving this questions:

* What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

* What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

* What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

* What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

5. Cache your temporary table home_sales and Check if your temporary table is cached.

6. Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

7. Partition by the "date_built" field on the formatted parquet home sales data.

8. Create a temporary table for the parquet data.

9. Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

10. Uncache the home_sales temporary table.

11. Verify that the home_sales temporary table is uncached using PySpark.


