# Movie-Recommendation-App
In this application, I have used the TMDB 5000 movies dataset from Kaggle:
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

Applied Processes
1. Data Cleaning
2. Data Fetching and Merge
3. Stemming
4. Vectorization
5. Making a Recommendation function
6. Building a WebApp using Streamlit library

Overview: In Jupyter Notebook, I performed Data Cleaning on the dataset and only kept useful movie tags.
Then, using those tags, I created arrays of 4000 elements for each movie.
Moreover, I made similarity metrics, with the distances of every movie from every other.
In the recommendation function, I used those metrics and the nearest 5 movie values to add those as suggested movies.
Lastly, using Streamlit, I made a WebApp making it fully functional Movie Recommendation Application

