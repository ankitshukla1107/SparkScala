# SparkScala

SECTION-1 - GETTING STARTED					
https://sundog-education.com/spark-scala/					
Download Java, Spark, winutils.exe, Scala IDE for eclipse					
Set JAVA_HOME, SPARK_HOME, HADOOP_HOME, and add in path					
Configure Spark log4j.properties to ERROR mode					
Debug Spark Scala programs and debug it on smaller daasets like Movielens data					
https://grouplens.org/datasets/movielens/					
Setup SparkScala project in Eclipse					
Upload Spark Jars					
Change Scala compiler in eclipse to Fixed Scala Installtion-2.11 					
					
SECTION-2 - SCALA CRASH COURSE					
Start Coding in following order-	Description				
					
1) RatingsCounter	Count up how many of each star rating exists in the MovieLens 100K data set				
2) Scala Crash Course-Create separate project	Basics of Scala required for Spark				
2.a LearningScala1	Scala Basics, Part-1 and Part-2				
2.b LearningScala2	Flow Control in Scala				
2.c LearningScala3	Functions in Scala				
2.d LearningScala4	Data Structures in Scala				
					
SECTION-3 - SPARK BASICS AND SIMPLE EXAMPLES					
Topics	--> Description				
3.1 Introduction to Spark	--> Architecture and Advantages of Spark				
3.2 RDD's	--> Transformations and Actions				
3.3 Ratings Histogram Walkthrough	--> RatingsCounter.scala				
3.4 Spark Internals	--> Stages, Tasks and Jobs				
3.5 Key/Value RDD's, and the Average Friends by Age example	--> FriendsByAge.scala				
3.6 Running Average Friends by Age example					
3.7 Filtering RDD's, and the Minimum Temperature by Location Example	--> MinTemperatures.scala				
3.8 Running the Minimum Temperature Example, and Modifying it for Maximum					
3.9 Counting Word Occurences using FlatMap()	--> WordCount.scala				
3.10 Improving the Word Count Script with Regular Expressions	--> WordCountBetter.scala				
3.11 Sorting the Word Count Results	--> WordCountBetterSorted.scala	--> Exercise: Filter out common words like is, am, ae, the			
3.12 Exercise: Find the Total Amount Spent by Customer	--> TotalSpentByCustomer.scala				
3.13 Exercise: Check your Results, and Sort them by Total Amount Spent	--> TotalSpentByCustomerSorted.scala				
					
SECTION-4: Advanced Examples of Spark Programs					
Topics	--> Description				
4.1 Find the Most Popular Movie					
4.2 Use Broadcast Variables to Display Movie Names  					
4.3 Find the Most Popular Superhero in a Social Graph					
4.4 Superhero Degrees of Separation: Introducing BFS					
4.5 Superhero Degrees of Separation: Accumulators, and Implementing BFS in Spark					
4.6 Item-Based Collaborative Filtering in Spark, cache(), and persist()					
4.7  Running the Similar Movies Script using Spark's Cluster Manager					
4.8 Improve the Quality of Similar Movies					
					
SECTION-5: Running Spark on a Cluster					
Topics					
5.1 Using spark-submit to run Spark driver scripts					
5.2 Packaging driver scripts with SBT					
5.3 Introducing Amazon Elastic MapReduce					
5.4 Creating Similar Movies from One Million Ratings on EMR					
5.5 Partitioning					
5.6 Troubleshooting and Managing Dependencies					
					
SECTION-6: SparkSQL, DataFrames, and DataSets					
6.1 Introduction to SparkSQL					
6.2 Activity: Using SparkSQL					
6.3 Activity: Using DataFrames and DataSets					
6.4 Activity: Using DataSets instead of RDD's					
