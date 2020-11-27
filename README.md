# spark-scala-seedling
A Spark Scala starter course


Switch to HIVE 
<code>
spark.sql("CREATE TABLE IF NOT EXISTS src (key INT, value STRING) USING hive")
spark.sql("CREATE TABLE IF NOT EXISTS employee(id INT, name STRING, age INT) ROW FORMAT DELIMITED FIELDS TERMINATED BY ',' LINES TERMINATED BY '\n' USING hive")
</code>

create a text file RDD from local file system

<code>val distFile = sc.textFile("$SPARK_HOME/../samples/docs/README.md")</code>

perform a map / reduce, return size of all lines to driver program

<code>val szLines = distFile.map(s => s.length).reduce((a,b) => a + b)</code>

<code>DROP TABLE IF EXISTS diamonds;

CREATE TABLE diamonds
USING csv
OPTIONS (path "/databricks-datasets/Rdatasets/data-001/csv/ggplot2/diamonds.csv", header "true")
</code>

<code></code>

<code></code>

<code></code>

<code></code>

<code></code>
