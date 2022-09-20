# SQL-QUERY-IMDB-DATASET-ANALYSIS-PROJECT
This Project is based on IMDB Dataset Analysis with the help of SQL as well as some Python Libraries 

IMDB Data Set Link :
https://www.kaggle.com/code/priy998/imdb-sqlite/data


# Try to Analysis 
1. How many are present in the movies table ?
2. Find out these 3 directors : James Cameron,Luc Besson,John Wo.
3. Find all the directors with the name starting with the 'Steven'
4. Count all the Feamle directors?
5. Find the name of the 10th First female director?
6. Find the Top 3 most popular movies
7. Find the Top 3 most bankable(budget) movie
8. Find out the most awarded average rated movie since Jan 1st, 2000?

# #use of libraries

Numpy-> To Perform the Mathematical Operation

Pandas-> Data Analysus-> DE,DM,DC,DV

Matplotlib-> Data Visulaization Tool

Seaborn-> Data Visulaization Tool

ReGex-> Data Cleaning 

sqlite3-> Database 

# Planning / Approach 

 Step 1: Connect your Database (or create a connection) -> sqlites3.connect(database_name)
 Step 2: Use the cursor function -> database_variable.cursor()
 Workflow
 1. You need to establish a connection to the SQLite Database by creating a connection object
 2. Then, you need to create a curson object using the cursor() method
 3. Then, excute the query -> cursor_variable.execute('query')
 4. To fectch the data, then use fetchall() method of the cursor variable/object
 5. You have to create a DataFrame w.r.t. the SQLite
 6. Data Analysis - Data Manipulation, Data Exploration, Data Cleaning, Data Visualisation
 7. Conclusion at every step
