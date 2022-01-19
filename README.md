# movie-recommender-system

https://lko-movie-recommender.herokuapp.com/

This is content based recommender system,so  created Tags  based on genres , keywords,overview,cast & crew for every movie .
-After preprocessing of data i have used Stamming and Bags_of_words(max_feature=5000) for vectorization .
-there are 4806 movies in dataset so there are 4806 vectors and in every vector there are 5000 numbers(co-ordinate dimention).
-since we are talking abt 5000 co-ordinate dimention and every movie is vector there so we need to calculate cosine_similarity of every movie to other all movies, Greater distance means lesser similarities and vise-versa .

 web-app --Streamlit Python library .
 
 fetch the movie poster -- url = "https://api.themoviedb.org/3/movie/{}?api_key=83181b0d813a3cff0139b45b7ec28295&language=en-US".format(
        movie_id).
        
 <img src="https://github.com/monika2910/movie-recommender-system/blob/main/output1.png"  width="900" height="500"  /><br><br>
        
        

