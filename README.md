# spark-scala-seedling
A Spark Scala starter course

some useful fs commands

<code>%fs ls databricks-datasets</code>

create a text file RDD from local file system

<code>val distFile = sc.textFile("/databricks-datasets/samples/docs/README.md")</code>

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
