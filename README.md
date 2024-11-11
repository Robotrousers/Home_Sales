### Challenge 22 Big Data
###  Home_Sales
#### Use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

### Answer the following questions using SparkSQL:
- What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
- What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
- What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
- What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

### Proposed Technologies:
```yaml
Python: Jupyter Notebook, pandas
pyspark.sql: SparkSQL
```

### This repo contains the following files:
```yaml
    root\
    - Home_Sales.ipynb - the Jupyter Notebook file with data work
    - README.md
```



### Resources, Cites and API
- *Class_Material 22-2-2* - basic spark code: imports, context etc
- *Class_Material 22-2-3* - date
- *Class_Material 22-3-3* - time
- *Class_Material 22-3-4* - partitioning
- *Class_Material 22-3-5* - caching

