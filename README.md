# song_recommendation
##Introduction
The aim of this project is to build a song recommender based on users pre-existing preferences.

The model will be trained on a dataset of songs and their attributes from varius spotify playlists, which will be gathered by web scraping from spotify using Python's web scraping libraries. We will be using Spotipy, a Python library for the Spotify Web API, to gather information about users' favorite artists and songs. 

To create our song recommender, we will use kmeans clustering to group songs into categories. We will then match a users input with songs that closely match it's attributes and suggest other songs they might like.

Overall, this project aims to create an intuitive and personalized music recommendation system that provides users with a seamless music discovery experience.
