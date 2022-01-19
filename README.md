# movie-recommender-system

https://lko-movie-recommender.herokuapp.com/

This is content based recommender system,so i created Tags  based on genres , keywords,overview,cast & crew for every movie .
-After preprocessing of data i used Stamming and for vectorization i used Bags_of_words(max_feature=5000).
-there are 4806 movies in my data so there are 4806 vectors and in every vector there are 5000 numbers(co-ordinate dimention).
-since we are talking abt 5000 co-ordinate dimention and every movie is vector there so we need to calculate cosine_similarity of every movie to other all movies, Greater distance- lesser similarities .

