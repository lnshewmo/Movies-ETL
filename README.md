# Movies - Extract, Transform, Load

## Overview

Amazing Prime would like to automate a pipeline which takes in movie data from 3 sources (Wikipedia, Kaggle and MovieLens) and performs an extract, transform, load process to a PostgreSQL database.  Existing code from a Hackathon was refactored using Python in a Jupyter Notebook to create one function to perform this operation.  The outputs are 2 tables in a movie_data database titled:  movies and ratings.

### Table: movies
The table has 22 columns and 6052 rows

<img src="https://github.com/lnshewmo/Movies-ETL/blob/main/Resources/movies_query.png" width=55% height=55%>

### Table: ratings
The table has 5 columns and 26024289 rows

<img src="https://github.com/lnshewmo/Movies-ETL/blob/main/Resources/ratings_query.png" width=55% height=55%>
