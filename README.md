# PROJECT-1 HIVE
## Project Description
BY using Hortonworks-sandbox in virtual Machine,i created directories in Hdfs and loaded the data in it,later on i created external tables using HiveQL and
analyzed the data using some aggregations like filtering and bucketing
## Technologies Used
* Hadoop
* hive
* Git
## Features
* fault tolerance
* Processing unstructured data
* MapReduce
* some queries are solved using HiveQL
 1.Number of Unique movies
 2.Maximum rating given to a movie
## Getting Started
* To start this project user need to install Hortonworks-sandbox in Virtual Machine.Connect to Vm through Git Bash using SSH command "ssh maria_dev@sandbox-hdp.hortonworks.com -p 2222" after that user need to give the password by default it is maria_dev 
* git clone https://github.com/sweety15/project1.git by using this we can pull the dataset 
* create a directory in hdfs(project1) and in that create three folders(movies,ratings,tags) using command hdfs dfs -mkdir /user/maria_dev/project1
* Later load the 3 datafile in the 3 specific folders hdfs dfs -put movies.csv /user/maria_dev/project1/movies
* create database database_name;
* use database_name;
* CREATE EXTERNAL TABLE <file name> (id int, name string, salary float)
  row format delimited
  fields terminated by ','
  location '/project1/file name'(specify the path of a directory for specific file) ;
* Now we can create queries and analyze the data
## Usage
* Create directories in hdfs
* Load the data
* Create External tables using HiveQL


