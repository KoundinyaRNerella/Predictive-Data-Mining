# Predictive-Data-Mining
We are aiming to build a model which takes the genre name and the release month as input and predicts how successful or unsuccessful the movie would be in terms of box office collections. 
We have chosen a simple goal of predicting the movie success based on it’s genre and release month. 
The data is taken from Kaggle and consists of metadata for all 45,000 movies listed in the Full MovieLens Dataset. The dataset consists of movies released on or before July 2017.
Data Link: https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset.
We have considered 'id', 'genres', 'budget', 'revenue', 'release_date' for building our prediction model.
Data cleaning and transformation for making the data suitable for our prediction technique.
Using vectorizer to make the input compatible with the classifier.
Using decision tree classifier for the classification of the data based on its box office success
Creating a tool which take genre and month as sample input and tells us how successful the movie would be. 
Th sample input format is "Animation-12", "Family-1", "Family-11" etc.,
