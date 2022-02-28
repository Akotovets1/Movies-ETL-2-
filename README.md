# Movies-ETL

## Purpose
Create an ETL pipeline from raw data to a SQL database. Extract data from several sources using Python. Clean and transform data using Pandas. Load data with PostgreSQL and verify in PgAdmin.

## Deliverable 1: Write an ETL Function to Read Three Data Files


### The Wiki_movies_df DataFrame:

![Pic 1](https://github.com/Akotovets1/Movies-ETL-2-/blob/main/Images/wiki_movies_df.png)

### The Kaggle_metadata DataFrame:

![Pic 2](https://github.com/Akotovets1/Movies-ETL-2-/blob/main/Images/kaggle_metadata.png)

### The Ratings DataFrame:

![Pic 3](https://github.com/Akotovets1/Movies-ETL-2-/blob/main/Images/ratings.png)

### File:
[ETL_function_test](https://github.com/Akotovets1/Movies-ETL-2-/blob/main/ETL_function_test.ipynb)

## Deliverable 2: Extract and Transform the Wikipedia Data

![Wiki_movies_df](https://github.com/Akotovets1/Movies-ETL-2-/blob/main/Images/D2_wiki_movies_df.png)

![Wiki_movies_df_columns](https://github.com/Akotovets1/Movies-ETL-2-/blob/main/Images/D2_wiki_movies_df_columns.png)

The cleaned Wikipedia data is converted to a Pandas DataFrame, and the DataFrame is displayed in the [ETL_clean_wiki_movies](https://github.com/Akotovets1/Movies-ETL-2-/blob/main/ETL_clean_wiki_movies.ipynb) file.

## Deliverable 3: Extract and Transform the Kaggle data

### DataFrames:

![Pic 4](https://github.com/Akotovets1/Movies-ETL-2-/blob/main/Images/D3.1_wiki_movies.png)


![Pic 5](https://github.com/Akotovets1/Movies-ETL-2-/blob/main/Images/D3.2_movies_with_ratings.png)


![Pic 6](https://github.com/Akotovets1/Movies-ETL-2-/blob/main/Images/D3.3_movies_df.png)

### File:
[ETL_clean_kaggle_data](https://github.com/Akotovets1/Movies-ETL-2-/blob/main/ETL_clean_kaggle_data.ipynb)

## Deliverable 4: Create the Movie Database

### File:
[ETL_create_database](https://github.com/Akotovets1/Movies-ETL-2-/blob/main/ETL_create_database.ipynb)

### The elapsed time to add the data to the database:

![Pic 7](https://github.com/Akotovets1/Movies-ETL-2-/blob/main/Images/D4_elapsed_time.png)

### The movies table in the SQL database:
![Pic 8](https://github.com/Akotovets1/Movies-ETL-2-/blob/main/Resources/movies_query.png)

### The ratings table in the SQL database:
![Pic 9](https://github.com/Akotovets1/Movies-ETL-2-/blob/main/Resources/ratings_query.png)


