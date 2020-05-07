## Project Purpose and Description

Sparkify (fake company) is back at it again and wants to continue to analyze the data they've been collecting on music and user activity on a new music streaming app.  This time, the data team is interested in specific queries.  Sparkify wants to create a NoSQL Database using Apache Cassandra to optimize for fast reads and writes.  In this project, I created a keyspace with tables to answer simple query questions.  

## Tools (all using Python and its various libraries)
   - Pandas
   - Apache Cassandra
   
## Data

The data is in the form of csv files where they will all be processed by a function that will create tables and insert data.  

### CSV File Foramt

   `2018-11-01-events.csv`


## Table Goals
 
Since joins are not optimized for NoSQL Databases, 3 Seperate tables will answer 3 different queries.  


<p align="center">
<img src="sparkify_cassandra_tables.jpeg.png" width="700" height="500">
</p>

## Repo Files
