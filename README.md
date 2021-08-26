# PROJECT-1 HIVE
## Project Description
Import csv data about movies ,ratings and their tags into HDFS, then create tables from the imported files in Hive. 
Once imported, create queries using HiveQL to analyze and display data.
Analyze the data using some aggregations like filtering and bucketing
## Technologies Used
* Hadoop
* hive
## Features
* fault tolerance
* Processing unstructured data
* MapReduce
## Getting Started
* git clone https://github.com/sweety15/project1.git
* create a directory in hdfs(project1) and in that create three folders(movies,ratings,tags) using command hdfs dfs -mkdir /user/maria_dev/project1
* Later load the 3 datafile in the 3 specific folders hdfs dfs -put movies.csv /user/maria_dev/project1/movies
* create database database_name;
* use database_name;
* CREATE EXTERNAL TABLE <file name> (id int, name string, salary float)
  row format delimited
  fields terminated by ','
  location '/project1/file name'(specify the path of a directory for specific file) ;
*Now we can create queries and analyze the data
## Usage
  

