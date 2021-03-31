# movie-recomendation-system
A simple movie recommendation system based on the Movie Lens 100K dataset. It compares a memory-based recommendation system based on
user-user similarity matrix and item-item similarity matrix. 
System implement method predict, that for a given user u and item i predicts a ranking given to the item by the user - either based on user-user similarity or
item-item similarity and predict rankings for test data.
It uses mean squared error as a validation metric on a test set.
