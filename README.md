# Movie Data Analysis with ETL

## Overview of Project

* Amazing Prime will host a Hackathon for local coders and will ask them to predict popular movies in the future. 
* Britta, who works for Amazing Prime, needs a clean dataset to use for the Hackathon. 

### Purpose

* Extract Wikipedia and Kaggle data on movies, transform the data, and load the cleaned data into a SQL database. Then, the data will be ready for the Hackathon.
* Create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. 

## ETL Process

### Write an ETL Function to Read Three Data Files

* View this process in ETL_function_test.ipynb. 
* The ETL function will read files for the Wiki movie data, Kaggle movie data, and Kaggle ratings data.

### Extract and Transform the Wiki Data

* View this process in ETL_clean_wiki_movies.ipynb.
* This file shows the process of transforming the Wiki data.

### Extract and Transform the Kaggle Data

* View this process in ETL_clean_kaggle_data.ipynb.
* This file shows the process of transforming the Kaggle data.

### Create the Movie Database

* View this process in ETL_create_database.ipynb.
* The transformed data is loaded to a SQL database.

#### Two Tables: Movies and Ratings

* Two tables: movies and ratings
* Verify correct number of rows for movies (6052) and ratings (26,024,289)

- Movies table: ![movies_query]('Resources/movies_query.png')
- Ratings table: ![ratings_query]('Resources/ratings_query.png)
