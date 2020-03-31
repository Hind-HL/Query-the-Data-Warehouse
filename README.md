# Query-the-Data-Warehouse
Aside from learning about Star, Snowflake and Fact Constellation schema we also gained insights into the DW-Architecture, conceptual modelling(ADAPT, ME/R Model), ETL process, querying the Data Warehouse and more.
Load data, query and optimize were the main tasks fullfilled during our practical exercises of data Warehouse during my master studies.
Here you a quick but not extensive overview of 

First, we created the schema of the TPC-H Benchmark then imported data into the data warehouse using the sqlldr.
We used the CUBE, ROLLUP and Union operator in order to understand the concept behind them.
![dw1](https://user-images.githubusercontent.com/61826522/78019248-a10fcf80-734f-11ea-8be3-67004ffa1761.png)

On the other hand, we have seen OLAP functions in SQL2003 such as RANK(),DENSE_RANK(),PERCENT_RANK(),..for ranking. In addition to reporting functions like SUM(X) OVER(PARTITION BY),etc.
