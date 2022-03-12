# How to Make a Hit: The Music of Today for the Listening of Tomorrow
---
## Overview
Our project involves using data compiled from the music application Spotify and will focus on analyzing what song features can be isolated and configured to predict the popularity of a given record. Using Machine learning we manipulate features such are tempo, loudness, danceability, etc., to scale our song lists against their popularity scores. All values have been computed and assigned by Spotify. Our data comes from two sources: our training data will come from a data set compiling a songs ranging from 1921-2020; and our testing data will come from the top 100 songs per year from 2010-2019.

## Final Model
The hyperparameters for this model were set with three layers. The first layer had ten units, the second fifteen, and the output layer of course had one. We ran the model using the Relu activation function for a total of 100 epochs These variables resulted in a total of 799 parameters for the model and returned an accuracy score of 87%. This model was then fitted and used to predict the popularity of our testing data set. We stored the predictive popularity and graphed it based on various features using MatPlot to judge for ourselves how accurately the model predicted popularity. 
