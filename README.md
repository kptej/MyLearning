# MyLearning
Practice session on python &amp; pyspark 

session that are used in this repo is to prcatice all the content on daily basis.

What is SparkContext
Since Spark 1.x, SparkContext is an entry point to Spark and is defined in org.apache.spark package. It is used to programmatically create Spark RDD, accumulators, and broadcast variables on the cluster. Its object sc is default variable available in spark-shell and it can be programmatically created using SparkContext class.

Note that you can create only one active SparkContext per JVM. You should stop() the active SparkContext before creating a new one.

spark sparkcontext
Source: spark.apache.org
The Spark driver program creates and uses SparkContext to connect to the cluster manager to submit Spark jobs, and know what resource manager (YARN, Mesos or Standalone) to communicate to. It is the heart of the Spark application.
https://sparkbyexamples.com/wp-content/uploads/2022/05/image04.png![image](https://github.com/user-attachments/assets/65826dc3-74e7-4a12-a58d-951178e26ba6)
