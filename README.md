
# Build a Movie Recommendation API using Scikit-Learn, Flask and Streamlit

## There are three type of recommendation system:
1.Collaborative Filtering
2.Content-Based
3.Hybrid approach
<hr>
# Here i used Content-Based recommendation.
<hr>

### what is a  Content-Based recommendation system ?
Content-Based recommendation works on the principle that if a user likes a certain item then we recommend the user a similar item based on the item’s features or attributes. So in our case, if a user likes a movie of a particular genre or an actor then we recommend a movie on similar lines to our user. So, if a user has watched the movie Joker then our recommendation system would predict movies similar to Joker or with the same cast as that of Joker if we consider the movie’s cast.

<hr>

# Source Datasets:- 
- TMDB 5000 Movies Dataset: https://www.kaggle.com/tmdb/tmdb-movie-metadata

## Dataset Overview


cast: Top 3 actors/actresses of the movies
genres: Top 3 genres of the movies
movie_id: TMDb and IMDb IDs for Hollywood and Bollywood movies
original_title: Title of the movies
plot: Basic overview of the movie

<hr>

# cleaning folder Description:-
## cleaningData.ipynb 
- cleaning/preprocessing the data set before getting into a recommendation



# Deployment folder Description:- 
## main.py
- The Flask app where we use the recommendation.py as a module and return the results in JSON format. 

<hr> 

# Data set Folder :- 
- Contains the dataset we have used to build our recommendation system.
