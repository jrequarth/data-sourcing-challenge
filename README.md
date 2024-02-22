# data-sourcing-challenge

<<<<<<< HEAD
This is challenge 6

We are asked to scrape movie review data from the NYTs and merge it with the TMDB database on the title of the movie.
The NYTs and TMDB data are scraped using JSON and then converted into a database.

NYT: reviews_list_db is 180 rows x 16 columns
TMDB: tmdb_db is 141 rows x 15 columns

The 2 databases are merged (inner merge), cleaned, and duplicates are dropped.

merged_db is 113 rows x 31 columns
The byline column is dropped leaving 30 columns

the data is exported as collected_data.csv
=======
This program is designed to combine 2 disparate datafiles. 
The New York Times API and The Movie DataBase API will be accessed and content downloaded. These datafiles will be merged, cleaned, and exported.
From the NYTs API, we will create a variable called reviews_list is a list that will contain 200 searches. This will then by changed to a Pandas DataFrame.
   The headline.main column will provide the exact movie title. A list of movie titles with then be created.
From The Movie Database API, we will use the movie list to get genres, spoken_languages, production_countries, and many other variables.
The databases will be merged via the title column. Duplicate rows are deleted and the index is reset.
  Variables:
    genres
    spoken_languages
    production_countries
The combined dataframe is exported to a CSV file without the index
>>>>>>> bc3ae4b04b5384a9eeb77c8f87f1b97b4490b743
