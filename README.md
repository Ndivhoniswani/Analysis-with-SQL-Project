# SQL-The-Movie-Database

### Project Overview
We will be exploring The Movie Database – an online movie and TV show database that houses some of the most popular movies and TV shows at your fingertips. The TMDb database supports 39 official languages used in over 180 countries daily and dates back all the way to 2008.

### Data Source
- The Movie Database
  
Note that the database will not be available here, due to copywrite issues.

### Tools
- SQL
- MYSQL Workbench
- Jupyter notebook

### Preparation 

- Step 1: Load and activate the SQL extension to allow us to execute SQL in a Jupyter notebook.
- Step 2: Establish a connection to the local database using the '%sql' magic command. Replace 'password' with our connection password and `db_name` with our database name.
- Step 3: View all tables in the database.

### Exploratory data analysis

EDA involved exploring the movie database to answer 5 key questions, such as:

1. Who won the Oscar for “Actor in a Leading Role” in 2015?
2. How many unique awards are there in the Oscars table?
3. How many movies are there that contain the word “Spider” within their title?
4. How many unique characters has "Vin Diesel" played so far in the database?
5. What are the genres of the movie “The Royal Tenenbaums”?


### Data analysis

Interesting code in our work:
``` 
%%sql
SELECT*
FROM movies
WHERE movies.title = 'The Royal Tenenbaums'
LIMiT 1; 
```

### Results/Findings

1. **Leonardo DiCaprio**, won the Oscar for “Actor in a Leading Role” in 2015.
2. The are **114** unique awards are there in the Oscars table.
3. The are **9**  movies that contain the word “Spider” within their title.
4. The are **16** unique characters "Vin Diesel" played so far in the database.
5. The “The Royal Tenenbaums” falls under **Drama, Comedy** genres.

