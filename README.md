# Hadoop_Spark_Windows_Install


# Download below softwares:
    i) https://archive.apache.org/dist/hadoop/common/hadoop-2.7.2/hadoop-2.7.2-src.tar.gz
    ii) https://github.com/anjijava16/Hadoop_Spark_Windows_Install/blob/master/hadoop2.7.2%20(1).zip
    iii) Install Java inside the work fodler (Copy from c:/program file /java to c:/work/java locatin)
                    C:\work\Java\jdk1.8.0_211
     iv) changes in files                
    
    
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



