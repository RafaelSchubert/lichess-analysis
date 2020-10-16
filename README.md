# Prediction Model for the Outcome of Chess Matches in Lichess

This project is my first attempt at analyzing a real dataset and developing a prediction model for it -- specifically, a classification model -- using supervised learning techniques.

The dataset used in this project can be found [here](https://www.kaggle.com/datasnaek/chess), at [Kaggle](https://www.kaggle.com/). It contains the data collected from just over 20,000 chess matches played on [Lichess](https://lichess.org/), a free, open-source online chess server.

## Goal

The goal was to develop a prediction model that was able to predict the outcome of any given chess match played on Lichess, with a minimum precision of 80%.

## Results

The resulting prediction model achieved a precision of 80.1%, which is very close to the minimum precision expected for it.

## Possible improvements

Unfortunately, the model did not fare well predicting the outcome for matches that ended in a draw. Further analysis on the patterns that lead to a tied game are required.
