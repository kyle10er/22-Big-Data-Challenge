# 22-Big-Data-Challenge
In this challenge, we used our knowledge of SparkSQL to determine key metrics about home sales data. Then we used Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.  Once we created the temporary views we used SQL queries to answer the following questions. 

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

The files were printed out into tables that can be read in the colaboratory notebook.  After answering the questions we then cached the table to compare the run time of the query.  When we initially run the code it takes longer than it did once we cached the table.  Then to even further speed up the process we partitioned the data and read it as a parquet file.  

All of the code was constructed using past examples from the University of Pennsylvania's Data Science and Visualization Bootcamp. 
