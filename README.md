# spark-scala-seedling
A Spark Scala starter course

# create a text file RDD from local file system
<code>val distFile = sc.textFile("/databricks-datasets/samples/docs/README.md")</code>
# perform a map / reduce, return size of all lines to driver program
<code>val szLines = distFile.map(s => s.length).reduce((a,b) => a + b)</code>

<code></code>

<code></code>

<code></code>

<code></code>

<code></code>

<code></code>
