# Movies - Extract, Transform, Load

## Overview

Amazing Prime would like to automate a pipeline which takes in data from 3 sources (Wikipedia, Kaggle and MovieLens) and performs an extract, transform, load process to a PostgreSQL database.  Existing Hackathon code was refactored using Python in a Jupyter Notebook to create one function to perform this operation.  The outputs are 2 tables in a movie_data database titled:  movies and ratings.

### Table: movies
The table has 22 columns and 6052 rows
![movies](https://github.com/lnshewmo/Movies-ETL/blob/main/movies%20query.png)

### Table: ratings
The table has 5 columns and 24289 rows
![ratings](https://github.com/lnshewmo/Movies-ETL/blob/main/ratings%20query.png)
