# Hadoop_Spark_Windows_Install


hdfs.cmd namenode -format
start-dfs.cmd && start-yarn.cmd

winutils.exe chmod 777 C:\tmp\hive

spark-shell.cmd

```


hdfs.cmd namenode -format
start-dfs.cmd
start-yarn.cmd

Create one tmp folder under c:\tmp\hive

winutils.exe chmod 777 c:\tmp\hive
spark-shell.cmd

spark.read.format("csv").option("header","true").option("delimiter",";").load(data)


//download java 8
http://www.oracle.com/technetwork/jav...

//download scala
https://www.scala-lang.org/download/2...


//download hadoop 
https://archive.apache.org/dist/hadoo...

https://drive.google.com/file/d/1gaTq...

//download spark

http://www-eu.apache.org/dist/spark/s...

hdfs.cmd namenode -format
start-dfs.cmd && start-yarn.cmd

winutils.exe chmod 777 C:\tmp\hive

spark-shell.cmd


C:/work/hadoop-2.7.2/etc/hadoop/core-site.xml,C:/work/hadoop-2.7.2/etc/hadoop/hdfs-site.xml

```



