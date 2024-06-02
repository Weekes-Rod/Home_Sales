# Home Sales Analysis

This project performs analysis on home sales data using PySpark.

## Before You Begin

1. **Create a new repository for this project called `Home_Sales`. Do not add this homework to an existing repository.**
   
2. **Clone the new repository to your computer:**

   ```sh
   git clone https://github.com/your-username/Home_Sales.git
   cd Home_Sales
   
3. Push your changes to GitHub.
   
##Instructions

1. Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

2. Import the necessary PySpark SQL functions for this assignment.

3. Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

4. Create a temporary table called home_sales.

5. Answer the following questions using SparkSQL:

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
Cache your temporary table home_sales.

Check if your temporary table is cached.

Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

Partition by the date_built field on the formatted parquet home sales data.

Create a temporary table for the parquet data.

Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

Uncache the home_sales temporary table.

Verify that the home_sales temporary table is uncached using PySpark.

Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.

Resources
PySpark Activities
Xpert Learning Assistant
