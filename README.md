# recommendation-system
A machine learning mini project (undergrad mini project) for a movie recommendation system using user based collaborative filtering and item based collaborative filtering methods.

The dataset used to implement this project was the MovieLens dataset collected by GroupLens Research. In
particular, the MovieLens 100k dataset is a stable benchmark dataset with 100,000 ratings given
by 943 users for 1682 movies, with each user having rated at least 20 movies.
This dataset consists of many files that contain information about the movies, the users, and the
ratings given by users to the movies they have watched. The ones that are of interest are the
following:
● u.item: the list of movies
● u.data: the list of ratings given by users

The chief purpose of our system is to recommend movies to its users based on their viewing
history and ratings that they provide. Personalized recommendation engines help millions of
people narrow the universe of potential films to fit their unique tastes. 

Collaborative filtering and content-based filtering are the are prime approaches to provide recommendations to users. 
Both of them are best applicable in specific scenarios because of their respective ups and downs. In
this project I have proposed a mixed approach such that both the algorithms complement each
other thereby improving performance and accuracy of the system.

Technical objective: The technical objectives will be implemented in Python. The system must
be able to predict movies based on the similar movies based on other viewer’s ratings and also
recommend movies based on the ratings given by this user also.

Experimental objective: The main experimental objective of this project is to predict the movies
based on the similar movies based on other’s ratings and also recommend movies based on one’s
own ratings.
