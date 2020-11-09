# OMDB-and-TasteDive-Movie-recomendation-using-REST-APIs

TasteDive documentation for the API is at https://tastedive.com/read/api. OMDB documentation for the API is at https://www.omdbapi.com/

OMDB needs API key. Just send a req they will provide you key instently.

This project will take you through the process of mashing up data from two different APIs to make movie recommendations. The TasteDive API lets you provide a movie (or bands, TV shows, etc.) as a query input, and returns a set of related items. The OMDB API lets you provide a movie title as a query input and get back data about the movie, including scores from various review sites (Rotten Tomatoes, IMDB, etc.).

You will put those two together. You will use TasteDive to get related movies for a whole list of titles. You’ll combine the resulting lists of related movies, and sort them according to their Rotten Tomatoes scores (which will require making API calls to the OMDB API)
