# Spark_SQL

Name of project : Spark Sql Project

Overview : 
The data files about news items and their respective social feedback on platforms are present in “data” folder.
The information about these files is provided in the file readme.txt
Using Apache Spark with any choice of language, complete the following tasks.
1. Apply following business rules on the data
a. Rule 1 : If title contains less than 12 alphabets then remove those rows
b. Rule 2 : If topic has any value other than following topics: ‘obama’, ‘economy’, ‘microsoft’ or ‘palestine’ then remove such rows
2. Save the IDLink values for the rows rejected by Rule 1 and Rule 2 in the files named ‘Rule1_reject_log.csv’ and ‘Rule2_reject_log.csv’ respectively.
3. Save the modified data in the file named “News_cleansed.csv”
4. Generate a report in the text file format having following information
a. Total number of records in the original file
b. Total number of records after applying business rules
c. Year-wise average Sentiment score of the text in the news items' headline for each topic
d. Year-wise average Sentiment score of the text in the news items' title for each topic
e. Top 10 most popular items by average Final value of the news items' popularity on Facebook, GooglePlus, LinkedIn
Refer to the file sample_report.txt
5. Save the SOCIAL FEEDBACK DATA from GooglePlus as well as Facebook for the topic ‘economy’ for the news published in 2015 in the file named ‘economy_social_feedback_2015’.
Use News.csv only for performing tasks 1,2 and 3.

Installaton :Apache Spark , eclipse, Java, Spark sql

Metadata : datsets

Sources : Na

Tools / Technologies used : Spark Sql, apache spark, Java

Deployment : Na
