# Apache Hadoop Basics

*Click <img src="https://github.com/learning-zone/hadoop-interview-questions/blob/master/assets/star.png" width="18" height="18" align="absmiddle" title="Star" /> if you like the project. Pull Request are highly appreciated.*

<br/>

## Table of Contents

* *[Hadoop Commands](hadoop-commands.md)*
* *[Apache Hive Interview Questions](apache-hive-questions.md)*
* *[Apache OOZIE Interview Questions](apache-oozie-questions.md)*
* *[Apache Spark Interview Questions](apache-spark-questions.md)*

<br/>

#### Q. What is shuffling?
#### Q. What are optimization techniques for hadoop?
#### Q. When more shuffling is better?
#### Q. How to handle small files in hadoop?
#### Q. What is federation mode in hadoop?
#### Q. What are different nodes in hadoop cluster?
#### Q. What is difference between backup node and secondary namenode?
#### Q. What is DistCp?
#### Q. What is Speculative execution?
#### Q. For a file of size MB how many blocks will be created on HDFS?
#### Q. Write a MapReduce program to add all the elements in a file. 
#### Q. What is the difference between hashset and hashmap ? 
#### Q. Write a Hive program to find the number of employees department wise in an organization. 
#### Q. How will you read a CSV file of 10GB and store it in the database as it is in just few seconds ? 
#### Q. How will a file of 100MB be stored in Hadoop ? 
#### Q. What is Difference between Secondary namenode, Checkpoint namenode & backupnod Secondary Namenode, a poorly named component of hadoop.
#### Q. What are the Side Data Distribution Techniques.
#### Q. What is shuffleing in mapreduce?
#### Q. What is partitioning?
#### Q. Can we change the file cached by Distributed Cache
#### Q. What if job tracker machine is down?
#### Q. Can we deploy job tracker other than name node?
#### Q. What are the four modules that make up the Apache Hadoop framework?
#### Q. Which modes can Hadoop be run in? List a few features for each mode.
#### Q. Where are Hadoop’s configuration files located?
#### Q. List Hadoop’s three configuration files.
#### Q. What are “slaves” and “masters” in Hadoop?
#### Q. How many datanodes can run on a single Hadoop cluster?
#### Q. What is job tracker in Hadoop?
#### Q. How many job tracker processes can run on a single Hadoop cluster?
#### Q. What sorts of actions does the job tracker process perform?
#### Q. How does job tracker schedule a job for the task tracker?
#### Q. What does the mapred.job.tracker command do?
#### Q. What is “PID”?
#### Q. What is “jps”?
#### Q. Is there another way to check whether Namenode is working?
#### Q. How would you restart Namenode?
#### Q. What is “fsck”?
#### Q. What is a “map” in Hadoop?
#### Q. What is a “reducer” in Hadoop?
#### Q. What are the parameters of mappers and reducers?
#### Q. Is it possible to rename the output file, and if so, how?
#### Q. List the network requirements for using Hadoop.
#### Q. Which port does SSH work on?
#### Q. What is streaming in Hadoop?
#### Q. What is the difference between Input Split and an HDFS Block?
#### Q. What does the file hadoop-metrics.properties do?
#### Q. Name the most common Input Formats defined in Hadoop? Which one  is default?
#### Q. What is the difference between TextInputFormat and KeyValueInputFormat class?
#### Q. What is InputSplit in Hadoop?
#### Q. How is the splitting of file invoked in Hadoop framework
#### Q. Consider case scenario: In M/R system,
#### Q. How many input splits will be made by Hadoop framework?
#### Q. What is the purpose of RecordReader in Hadoop?
#### Q. After the Map phase finishes, the Hadoop framework does “Partitioning, Shuffle and sort”. Explain what happens in this phase?
#### Q. If no custom partitioner is defined in Hadoop then how is data partitioned before it is sent to the reducer?
#### Q. What is JobTracker?
#### Q. What are some typical functions of Job Tracker?
#### Q. What is TaskTracker?
#### Q. What is the relationship between Jobs and Tasks in Hadoop?
#### Q. Suppose Hadoop spawned 100 tasks for a job and one of the task failed. What will Hadoop do?
#### Q. Hadoop achieves parallelism by dividing the tasks across many nodes, it is possible for a few slow nodes to rate-limit the rest of the program and slow down the program. What mechanism Hadoop provides to combat this?
#### Q. How does speculative execution work in Hadoop?  
#### Q. Using command line in Linux, how will you
#### Q. What is Hadoop Streaming?  
#### Q. What is the characteristic of streaming API that makes it flexible run MapReduce jobs in languages like Perl, Ruby, Awk etc.?
#### Q. What is Distributed Cache in Hadoop?
#### Q. Is it possible to provide multiple input to Hadoop? If yes then how can you give multiple directories as input to the Hadoop job?
#### Q. Is it possible to have Hadoop job output in multiple directories? If yes, how?
#### Q. What will a Hadoop job do if you try to run it with an output directory that is already present? Will it
#### Q. How can you set an arbitrary number of mappers to be created for a job in Hadoop?
#### Q. How can you set an arbitrary number of Reducers to be created for a job in Hadoop?
#### Q. How will you write a custom partitioner for a Hadoop job?
#### Q. How did you debug your Hadoop code?
#### Q. What is BIG DATA?
#### Q. Can you give some examples of Big Data?
#### Q. Can you give a detailed overview about the Big Data being generated by Facebook?
#### Q. According to IBM, what are the three characteristics of Big Data?
#### Q. How Big is ‘Big Data’?
#### Q. How analysis of Big Data is useful for organizations?
#### Q. Who are ‘Data Scientists’?
#### Q. What are some of the characteristics of Hadoop framework?
#### Q. Give a brief overview of Hadoop history.
#### Q. Give examples of some companies that are using Hadoop structure?
#### Q. What is the basic difference between traditional RDBMS and Hadoop?
#### Q. What is structured and unstructured data?
#### Q. What are the core components of Hadoop?
#### Q. What is HDFS?
#### Q. What are the key features of HDFS?
#### Q. What is Fault Tolerance?
#### Q. Replication causes data redundancy then why is is pursued in HDFS?
#### Q. Since the data is replicated thrice in HDFS, does it mean that any calculation done on one node will also be replicated on the other two?
#### Q. What is throughput? How does HDFS get a good throughput?
#### Q. What is streaming access?
#### Q. What is a commodity hardware? Does commodity hardware include RAM?
#### Q. What is a metadata?
#### Q. Why do we use HDFS for applications having large data sets and not when there are lot of small files?
#### Q. What is a daemon?
#### Q. Is Namenode machine same as datanode machine as in terms of hardware?
#### Q. What is a heartbeat in HDFS?
#### Q. Are Namenode and job tracker on the same host?
#### Q. What is a ‘block’ in HDFS?
#### Q. What are the benefits of block transfer?
#### Q. If we want to copy 10 blocks from one machine to another, but another machine can copy only 8.5 blocks, can the blocks be broken at the time of replication?
#### Q. How indexing is done in HDFS?
#### Q. If a data Node is full how it’s identified?
#### Q. If datanodes increase, then do we need to upgrade Namenode?
#### Q. Are job tracker and task trackers present in separate machines?
#### Q. When we send a data to a node, do we allow settling in time, before sending another data to that node?
#### Q. Does hadoop always require digital data to process?
#### Q. On what basis Namenode will decide which datanode to write on?
#### Q. Doesn’t Google have its very own version of DFS?
#### Q. Who is a ‘user’ in HDFS?
#### Q. Is client the end user in HDFS?
#### Q. What is the communication channel between client and namenode/datanode?
#### Q. What is a rack?
#### Q. On what basis data will be stored on a rack?
#### Q. Do we need to place 2nd and 3rd data in rack 2 only?
#### Q. What if rack 2 and datanode fails?
#### Q. What is a Secondary Namenode? Is it a substitute to the Namenode?
#### Q. What is the difference between Gen1 and Gen2 Hadoop with regards to the Namenode?
#### Q. What is ‘Key value pair’ in HDFS?
#### Q. What is the difference between MapReduce engine and HDFS cluster?
#### Q. Is map like a pointer?
#### Q. Do we require two servers for the Namenode and the datanodes?
#### Q. Why are the number of splits equal to the number of maps?
#### Q. Is a job split into maps?
#### Q. Which are the two types of ‘writes’ in HDFS?
#### Q. Why ‘Reading‘ is done in parallel and ‘Writing‘ is not in HDFS?
#### Q. Can Hadoop be compared to NOSQL database like Cassandra?
#### Q. How can I install Cloudera VM in my system?
#### Q. What is a Task Tracker in Hadoop? How many instances of Task Tracker run on a hadoop cluster
#### Q. What are the four basic parameters of a mapper?	
#### Q. What is the input type/format in MapReduce by default?
#### Q. Can we do online transactions(OLTP) using Hadoop?	SRVMTrainings
#### Q. Explain how HDFS communicates with Linux native file system	
#### Q. What is a JobTracker in Hadoop? How many instances of JobTracker run on a Hadoop Cluster?
#### Q. What is the InputFormat ?	
#### Q. What is the InputSplit in map reduce ?	
#### Q. What is a IdentityMapper and IdentityReducer in MapReduce ?
#### Q. How JobTracker schedules a task?
#### Q. When is the reducers are started in a MapReduce job?
#### Q. On What concept the Hadoop framework works?	
#### Q. What is a DataNode? How many instances of DataNode run on a Hadoop Cluster?	
#### Q. What other technologies have you used in hadoop sta ck?	
#### Q. How NameNode Handles data node failures?	
#### Q. How many Daemon processes run on a Hadoop system?	
#### Q. What is configuration of a typical slave node on Hadoop cluster?
#### Q.  How many JVMs run on a slave node?	
#### Q. How will you make changes to the default configuration files?	
#### Q. Can I set the number of reducers to zero?	
#### Q. Whats the default port that jobtrackers listens ?	
#### Q. unable to read options file while i tried to import data from mysql to hdfs.	Narendra	
#### Q. What problems have you faced when you are working on Hadoop code?	
#### Q. how would you modify that solution to only count the number of unique words in all the documents?	
#### Q. What is the difference between a Hadoop  and Relational Database and Nosql?	
#### Q. How the HDFS Blocks are replicated?	
#### Q. What is a Task instance in Hadoop? Where does it run?
#### Q. what is meaning Replication factor?	
#### Q. If reducers do not start before all mappers finish then why does the progress on MapReduce job shows something like Map(50%) Reduce(10%)? Why reducers progress percentage is displayed when mapper is not finished yet?
#### Q. How the Client communicates with HDFS?	
#### Q. Which object can be used to get the progress of a particular job 
#### Q. What is next step after Mapper or MapTask?	
#### Q. What are the default configuration files that are used in Hadoop?
#### Q. Does MapReduce programming model provide a way for reducers to communicate with each other? In a MapReduce job can a reducer communicate with another reducer?
#### Q. What is HDFS Block size? How is it different from traditional file system block size?
#### Q. what is SPF?	
#### Q. Where do you specify the Mapper Implementation?	
#### Q. What is a NameNode? How many instances of NameNode run on a Hadoop Cluster?
#### Q. Explain the core methods of the Reducer?
#### Q. What is Hadoop framework?
#### Q. Is it possible to provide multiple input to Hadoop? If yes then how can you give multiple directories as input to the Hadoop job
#### Q. How would you tackle counting words in several text documents?	
#### Q. How does master slave architecture in the Hadoop?	
#### Q. How would you tackle calculating the number of unique visitors for each hour by mining a huge Apache log? You can use post processing on the output of the MapReduce job.	
#### Q. How did you debug your Hadoop code ?	
#### Q. How will you write a custom partitioner for a Hadoop job?	
#### Q. How can you add the arbitrary key-value pairs in your mapper?
#### Q. what is a datanode?	
#### Q. What are combiners? When should I use a combiner in my MapReduce Job?	
#### Q. How Mapper is instantiated in a running job?
#### Q. Which interface needs to be implemented to create Mapper and Reducer for the Hadoop?	
#### Q. What happens if you don?t override the Mapper methods and keep them as it is?	
#### Q. How does an Hadoop application look like or their basic components?
#### Q. What is the meaning of speculative execution in Hadoop? Why is it important?	
#### Q. What are the restriction to the key and value class ?
#### Q. Explain the WordCount implementation via Hadoop framework ?
#### Q. What Mapper does?	
#### Q. what is MAP REDUCE?	
#### Q. Explain the Reducer?s Sort phase?	
#### Q. What are the primary phases of the Reducer?	
#### Q. Explain the Reducer's reduce phase?	
#### Q. Explain the shuffle?	
#### Q. What happens if number of reducers are 0?	
#### Q. How many Reducers should be configured?	
#### Q. What is Writable & WritableComparable interface?	
#### Q. What is the Hadoop MapReduce API contract for a key and value Class?	
#### Q. Where is the Mapper Output (intermediate kay-value data) stored ?	
#### Q. What is the difference between HDFS and NAS ?	
#### Q. Whats is Distributed Cache in Hadoop	
#### Q. Have you ever used Counters in Hadoop. Give us an example scenario?	
#### Q. can we write map reduce program in other than java programming language. how.
#### Q. What alternate way does HDFS provides to recover data in case a Namenode, without backup, fails and cannot be recovered?	
#### Q. What is the use of Context object?	
#### Q. What is the Reducer used for?	
#### Q. What is the use of Combiner?	
#### Q. Explain how input and output data format of the Hadoop framework?
#### Q. What is compute and Storage nodes?	
#### Q. what is namenode?	
#### Q. How does Mappers run() method works?
#### Q. what is the default replication factor in HDFS?	
#### Q. It can be possible that a Job has 0 reducers?	
#### Q. How many maps are there in a particular Job?	
#### Q. How many instances of JobTracker can run on a Hadoop Cluser?	
#### Q. How can we control particular key should go in a specific reducer?	
#### Q. what is the typical block size of an HDFS block?	
#### Q. What do you understand about Object Oriented Programming (OOP)? Use Java examples.	
#### Q. What are the main differences between versions 1.5 and version 1.6 of Java?	
#### Q. Describe what happens to a MapReduce job from submission to output?	
#### Q. What mechanism does Hadoop framework provides to synchronize changes made in Distribution Cache during runtime of the application	
#### Q. Did you ever built a production process in Hadoop ? If yes then what was the process when your hadoop job fails due to any reason	
#### Q. Did you ever ran into a lop sided job that resulted in out of memory error, if yes then how did you handled it	
#### Q. What is HDFS ? How it is different from traditional file systems?	
#### Q. What is the benifit of Distributed cache, why can we just have the file in HDFS and have the application read it	
#### Q. How JobTracker schedules a task?
#### Q. How many Daemon processes run on a Hadoop system?
#### Q. What is configuration of a typical slave node on Hadoop cluster? How many JVMs run on a slave node?
#### Q. What is configuration of a typical slave node on Hadoop cluster? How many JVMs run on a slave node?
#### Q. What is the difference between HDFS and NAS ?
#### Q. How NameNode Handles data node failures?
#### Q. Does MapReduce programming model provide a way for reducers to communicate with each other? In a MapReduce job can a reducer communicate with another reducer?
#### Q. Where is the Mapper Output (intermediate kay-value data) stored ?
#### Q. What are combiners? When should I use a combiner in my MapReduce Job?
#### Q. What is a IdentityMapper and IdentityReducer in MapReduce ?
#### Q. When is the reducers are started in a MapReduce job?
#### Q. If reducers do not start before all mappers finish then why does the progress on MapReduce job shows something like Map(50%) Reduce(10%)? Why reducers progress percentage is displayed when mapper is not finished yet?
#### Q. What is HDFS Block size? How is it different from traditional file system block size?
#### Q. How the Client communicates with HDFS?
#### Q. What is NoSQL?
#### Q. We have already SQL then Why NoSQL? 
#### Q. What is the difference between SQL and NoSQL?
#### Q. Is NoSQL follow relational DB model?
#### Q. Why would NoSQL be better than using a SQL Database? And how much better is it?
#### Q. What do you understand by Standalone (or local) mode?
#### Q. What is Pseudo-distributed mode?
#### Q. What does /var/hadoop/pids do?
#### Q. Pig for Hadoop - Give some points?
#### Q. Hive for Hadoop - Give some points?
#### Q. File permissions in HDFS?
#### Q. what is ODBC and JDBC connectivity in Hive?
#### Q. What is Derby database?
#### Q. What is Schema on Read and Schema on Write?
#### Q. What infrastructure do we need to process 100 TB data using Hadoop?
#### Q. What is Internal and External table in Hive?
#### Q. what is Small File Problem in Hadoop
#### Q. How does a client read/write data in HDFS?
#### Q. What should be the ideal replication factor in Hadoop?
#### Q. What is the optimal block size in HDFS?
#### Q. explain Metadata in Namenode
#### Q. how to enable recycle bin or trash in Hadoop
#### Q. what is difference between int and intwritable
#### Q. How to change Replication Factor (For below cases):
#### Q. In Map Reduce why map write output to Local Disk instead of HDFS?
#### Q. Rack awareness of Namenode
#### Q. Hadoop the definitive guide (2nd edition) pdf
#### Q. What is bucketing in Hive?
#### Q. What is Clustring in Hive?
#### Q. What type of data we should put in Distributed Cache? When to put the data in DC? How much volume we should put in?
#### Q. What is Distributed Cache?
#### Q. What is Partioner in hadoop? Where does it run,mapper or reducer?
#### Q.  what are mapreduce new and old apis while writing map reduce program . explain how it works
#### Q. How to write a Custom Key Class?
#### Q. What is the utility of using Writable Comparable (Custom Class) in Map Reduce code?
#### Q. What are Input Format, Input Split & Record Reader and what they do?
#### Q. Why we use IntWritable instead of Int? Why we use LongWritable instead of Long?
#### Q. How to enable Recycle bin in Hadoop?
#### Q. If data is present in HDFS and RF is defined, then how can we change Replication Factor?
#### Q. How we can change Replication factor when Data is on the fly?
#### Q. mkdir: org.apache.hadoop.hdfs.server.namenode.SafeModeException: Cannot create directory /user/hadoop/inpdata. Name node is in safemode.
#### Q. What Hadoop Does in Safe Mode
#### Q. What should be the ideal replication factor in Hadoop Cluster?
#### Q. Heartbeat for Hadoop
#### Q. What will be the consideration while we do Hardware Planning for Master in Hadoop architecture?
#### Q. When should be hadoop archive create
#### Q. what factors the block size takes before creation?
#### Q. In which location Name Node sores its Metadata and why?
#### Q. Should we use RAID in Hadoop or not?
#### Q. How blocks are distributed among all data nodes for a particular chunk of data?
#### Q. How to enable Trash/Recycle Bin in Hadoop?
#### Q. what is hadoop archive
#### Q. How to create hadoop archive
#### Q. How we can take Hadoop out of Safe Mode
#### Q. What is safe mode in Hadoop?
#### Q. Why Mapreduce output written in local disk
#### Q. When Hadoop Enter in Safe Mode
#### Q. Data node block size in HDFS, why 64MB?
#### Q. What is the Non DFS Used
#### Q. Virtual Box & Ubuntu Installation
#### Q. What is Rack awareness?
#### Q. On what basis name node distribute blocks across the data nodes?
#### Q. What is Output Format in hadoop?
#### Q. How to write data in Hbase using flume?
#### Q. What is difference between memory channel and file channel in flume?
#### Q. How to create table in hive for a json input file.
#### Q. What is speculative execution in Hadoop?
#### Q. What is a Record Reader in hadoop?
#### Q. How to resolve the following error while running a query in hive: Error in metadata: Cannot validate serde
#### Q. What is difference between internal and external tables in hive?
#### Q. What is Bucketing and Clustering in Hive?
#### Q. How to enable/configure the compression of map output data in hadoop?
#### Q. What is InputFormat in hadoop?
#### Q. How to configure hadoop to reuse JVM for mappers?
#### Q. What is difference between split and block in hadoop?
#### Q. What is Input Split in hadoop?
#### Q. How can one write custom record reader?
#### Q. What is balancer? How to run a cluster balancing utility?
#### Q. What is version-id mismatch error in hadoop?
#### Q. How to handle bad records during parsing?
#### Q. What is identity mapper and reducer? In which cases can we use them?
#### Q. What is Reduce only jobs?
#### Q. What is crontab? Explain with suitable example.
#### Q. Safe-mode execeptions
#### Q. What is the meaning of the term "non-DFS used" in Hadoop web-console?
#### Q. What is AMI
#### Q. Can we submit the mapreduce job from slave node?
#### Q. How to resolve small file problem in hdfs?
#### Q. How to overwrite an existing output file during execution of mapreduce jobs?
#### Q. What is difference between reducer and combiner?
#### Q. What do you understand from Node redundancy and is it exist in hadoop cluster 
#### Q. how to proceed to write your first mapreducer program.
#### Q. How to change replication factor of files already stored in HDFS
#### Q. How to resolve IOException: Cannot create directory, while formatting namenode in hadoop.
#### Q. How can one set space quota in Hadoop (HDFS) directory
#### Q. How can one increase replication factor to a desired value in Hadoop?

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>
