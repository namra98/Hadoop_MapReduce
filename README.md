# Hadoop_MapReduce

Running Your First MapReduce in Hadoop & Java:

Step 1: Download Code and Data 
•	Download it from: 
Step 2: Start Hadoop Cluster
•	Start-all.cmd
Step 3: Create an input directory in HDFS.
•	hadoop fs -mkdir /input_dir
Step 4: Copy the input text file named input_file.txt in the input directory (input_dir)of HDFS.
•	hadoop fs -put C:/input_file.txt /input_dir
Step 5: Verify input_file.txt available in HDFS input directory (input_dir).
•	hadoop fs -ls /input_dir/
Step 6: Verify content of the copied file.
•	Verify content of the copied file.
Step 7: Run MapReduceClient.jar and provide input and out directories.
•	hadoop jar MapReduceClient.jar wordcount /input_dir /output_dir
Step 8: Verify content for generated output file.
•	hadoop dfs -cat /output_dir/*
Step 8: Save content of generated output file to local disk.
•	hadoop dfs -get /output_dir/* localfolder

