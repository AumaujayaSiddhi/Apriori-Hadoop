# Apriori Algorithm Implementation using Hadoop MapReduce
This repository contains a implementation of the Apriori algorithm using Hadoop MapReduce. The Apriori algorithm is a method used for frequent itemset mining and deriving association rules from large datasets. By using the distributed computing capabilities of Hadoop, this implementation efficiently processes massive datasets to uncover hidden patterns and associations.

#### Prerequisites:
1. Hadoop environment (single-node or multi-node cluster), I tested algorithm on single node cluster environment. To do it on multi-node cluster a small code changes might require for k frequent itemset mapper.
2. Java Development Kit (JDK), I used JAVA11. Use JAVA8 or later
3. Input dataset of transactions in a supported format. Please see the input file attached

#### How to Run:
1. Single-node or Multi-node hadoop environment.
2. Input data should be present in the Hadoop Distributed File System(HDFS).
3. Compile the Java code(I used eclipse to do that) and package it into a JAR file.
4. Run apriori_run.bat file with neccessary changes
5. Retrieve the results from the HDFS output directory. You can even include this command as part of above bat file

### Applications of Apriori Algorithm:
1. Market Basket Analysis
2. Recommendation Systems
3. Web Usage Mining
4. Bioinformatics

#### Learning:
1. Hadoop official website(https://hadoop.apache.org/docs/stable/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html)
2. Tutorials point(https://www.tutorialspoint.com/hadoop/index.htm)
3. Wikipedia (https://en.wikipedia.org/wiki/Apache_Hadoop)

**Note**: I have not written code for finding association files at the end after frequent itemsets are found. If required write small java application to accomplish that.
