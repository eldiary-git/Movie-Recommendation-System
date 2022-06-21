Movie Recommendation System 

DL Project that give user many recommended movies to watch based on his search which focus on the name of the movie and it's Category, the Keywords or Titles of the Movie.
We use Many libraries and Models like (cosine similarity) which help us to find the best matches of the movies.
Document Localization:
We get the best matching results by applying these steps:
•	First, we define the dataset and choose the columns that we need then we remove the empty fields (null results).

•	Second, compining the selected features which is (Genres, Keywords, tagline, cast, director), then we use (cosine_similarity ) to get the similar movies.

•	Third , finally we creating the Movie Recommendation System which help us to get the close match results based on user search.
