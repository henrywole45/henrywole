# henrywole
## kuj,iuytuyt

``` sql
      SELECT category,
      (SELECT AVG(sales) FROM `sample-superstore-complete`) AS Overall_avg,
      SELECT ROUND(SUM(sales),2) FROM `sample-superstore-complete`) AS overall_total_sales,
      SELECT ROUND(SUM(sales),2) FROM `sample-superstore-complete
````

```` sql
SELECT AVG(sales) FROM `sample-superstore-complete`;-- first query

SELECT AVG(sales), category FROM `sample-superstore-complete` GROUP BY category;-- second query
````
