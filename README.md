# data-sourcing-challenge

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
The combined dataframe is exported to a CSV file without the index.
