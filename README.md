# How to Make a Hit: The Music of Today for the Listening of Tomorrow
---
## Overview
Our project involves using data compiled from the music application Spotify and will focus on analyzing what song features can be isolated and configured to predict the popularity of a given record. Using Machine learning we manipulate features such are tempo, loudness, danceability, etc., to scale our song lists against their popularity scores. All values have been computed and assigned by Spotify. Our data comes from two sources: our training data will come from a data set compiling a songs ranging from 1921-2020; and our testing data will come from the top 100 songs per year from 2010-2019.

## Usability
The goal of our project is to create a machine learning model that can be used to predict the popularity score of a song based on its features. This will allow for producers and businesses alike to input an array of features and then receive a score back. Music has gotten more complicated with new genres coming up like escape room and bro step, so we are looking to streamline the features of songs to see what will be popular based on features regardless of genre.

## Final Model
The hyperparameters for this model were set with four layers. An input layer, two hidden layers consisting 18 and 10 units, and then an output layer. We ran the model using the Relu activation function for a total of 100 epochs These variables resulted in a total of 799 parameters for the model and returned an accuracy score of 87%. This model was then fitted and used to predict the popularity of our testing data set. We stored the predictive popularity and graphed it based on various features using MatPlot to judge for ourselves how accurately the model predicted popularity. 

Additionally the model is also fitted to accept datasets without year as the year variable could became a hinderence to the score for future use since it was shown to be very impactful on the model's accuracy score. Without the year variable the model's accuracy still receives an accuracy score of almost 83%. This model can be used to predict scores of songs in the future based solely off of the components of the song and could be the framework for a mobile application either for work or entertainment.
