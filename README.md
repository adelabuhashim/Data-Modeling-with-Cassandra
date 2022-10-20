# Data-Modeling-with-Cassandra
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.  I will create an Apache Cassandra database which can create queries on song play data to answer the questions by crationg database for this analysis. and testing the database by running queries given by the analytics team from Sparkify to create the results.

## Files:
1. `Project_1B_ Project_Template.ipynb` The code file.


## Project Steps
### Modeling NoSQL database or Apache Cassandra database
1. Design tables to answer exact the queries.
2. Write Apache Cassandra `CREATE KEYSPACE` and `SET KEYSPACE` statements.
3. Develop the `CREATE` statement for each of the tables to address each question.
4. Load the data with `INSERT` statement for each of the tables.
5. Test by running the proper select statements with the correct `WHERE` clause.
### Build ETL Pipeline
1. Implement the logic to iterate through each event file in `event_data` to process and create a new CSV file in Python.
2. Include Apache Cassandra `CREATE` and `INSERT` statements to load processed records into relevant tables in the data model.
3. Test by running `SELECT` statements after running the queries on the database.


## Queries:
1. Give me the artist, song title and song's length in the music app history that was heard during sessionId = 338, and itemInSession = 4
2. Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
3. Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'