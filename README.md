# Home_Sales
Using SparkSQL, I was able to determine key metrics about home sales data to answer the following questions:

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

![image](https://github.com/SheTroxel/Home_Sales/assets/117420486/819997a5-af38-404a-bb19-4a41e59531ab)


What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

![image](https://github.com/SheTroxel/Home_Sales/assets/117420486/85839e26-1123-4cd4-871c-ca0fbce2cbe7)


What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

![image](https://github.com/SheTroxel/Home_Sales/assets/117420486/9f25e818-24e5-4b79-983e-412f65e102fe)


What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.. 

![image](https://github.com/SheTroxel/Home_Sales/assets/117420486/a83a5a8f-b489-4d81-89f6-bb03d7468c1a)


Using SparkSQL, I created temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached. 

After determining key metrics, I cached the temmpory table. Using the cached data, I ran a query that filters out the view ratings with an average price of greater than or equal to $350,000. Determined runtime and compare it to the uncached runtime.

I then formatted the data to create a parquet home sales data set, created a temporary table for the parquet data, and ran a query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

--------------------------------------------------------------------------------
References:
MSU Data Analytics Bootcamp Class Activites
Chat GBT to confirm code, trouble shoot
