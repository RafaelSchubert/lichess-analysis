# Prediction Model for the Outcome of Chess Matches on Lichess

This project is my first attempt at analyzing a real dataset and developing a prediction model for it -- specifically, a classification model -- using supervised learning techniques.

## Goal

The goal was to develop a prediction model that was able to predict the outcome of any given chess match played on [Lichess](https://lichess.org/) (a free, open-source online chess server), with a minimum precision of 80%.

Three classification algorithms were tested and compared, of which that with the best performance was chosen to build the final prediction model:

- Decision Tree;
- Multi-Class Logistic Regression;
- Random Forest.

## Artifacts

### 1) The Dataset

The dataset used in this project can be found [here](https://www.kaggle.com/datasnaek/chess), at [Kaggle](https://www.kaggle.com/) (an online data science community). It contains the data collected from just over 20,000 chess matches played on Lichess.

### 2) The Analysis

In the `analysis.ipynb` notebook file, you will find the whole process I went through:

- assessment of the dataset's integrity;
- data cleaning;
- exploratory analysis;
- choice of classification algorithm;
- model building and training;
- and model testing.

The analysis was performed in the [Google Colab](https://colab.research.google.com/) environment using [Python](https://www.python.org/) as the programming language of choice, along with some of its well-known libraries: [Matplotlib](https://matplotlib.org/), [NumPy](https://numpy.org/), [Pandas](https://pandas.pydata.org/), [Scikit-Learn](https://scikit-learn.org/) and [SciPy](https://www.scipy.org/).

Keep in mind that this was a very extensive analysis, so it is a long read. If you are interested, grab a cup of coffee or tea of your choice and take it easy. ;)

### 3) The Poster

The activity required us to analyze a dataset, seeking to solve a prediction problem -- both of our choice --, and to produce an A3-size poster about the process and our findings. This poster is what you will find in the `poster_pt-br.pdf` PDF file.

## Results

Of the three candidate algorithms, the Random Forest classifier achieved the best performance, with a precision of 80,7%.

The final prediction model achieved a precision of 80.1%, which is very close to the minimum precision expected for it.

## Possible improvements

Unfortunately, the model did not fare well predicting the outcome for matches that ended in a draw. Further analysis on the patterns that lead to a tied game are required.
