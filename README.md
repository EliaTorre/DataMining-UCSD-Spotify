<h1 align="center">
Spotify Song Popularity & Content-Based Recommendation System</h1>

<div align="center">
  <a href="https://www.linkedin.com/in/eliatorre/">Elia Torre</a>
  <p><a href="https://datascience.ucsd.edu/">Halıcıoğlu Data Science Institute</a>, UC San Diego, La Jolla, CA</p>
</div>

>**<p align="justify"> Abstract:** *This repository presents the research undertaken in the Final Project for DSC190 - Introduction to Data Mining course. The purpose of this project is dual. In the first part of the associated notebook, Spotify Songs Dataset will be explored with the aim of developing and fine-tuning two Regression Models (XGBRegressor and Random-Forest Regressor) to predict the popularity of a song and evaluating their performance against a baseline model (LinearRegression). In a second section, in light of a deeper understanding of the dataset and its characteristics, we delve into the construction of a Content-Based Recommendation System which relies on "vectorization" and Cosine Similarity. In this second part of the project, the user can interact with the system to receive song recommendations starting from one of its Spotify playlists.*

<hr/>

## Dataset
The dataset used to perform the following analysis is a dataframe containing approximately 170k songs, it covers an heterogeneous range of genres on a timeframe from 1921 to 2020. It can be retrieved from Kaggle at: [Kaggle Dataset](https://www.kaggle.com/code/vatsalmavani/music-recommendation-system-using-spotify-dataset/input).

<hr/>

## Prediction Task

### Models & Training
Since we are dealing with a regression task, i.e., we are regressing the features of the dataset to predict the popularity of a song, **LinearRegression** will be used as a baseline model. Indeed, it represents the simplest model and "building block" of regression analysis. Then, **XGBRegressor**, i.e. a very robust boosting algorithm which is often exploited in Data Science competitions due to its ability of achieving good performance with relatively simple hyperparameters optimization, will be implemented. In addition, also **RandomForestRegressor**, i.e., a tree-based decision algorithm that exploits bagging and randomness, will be tried. The performance of these three algorithms will be evaluated according to **Mean Squared Error**. The MSE obtained by the three architectures before any hyperarameter tuning is the following:
  • LinearRegression: 119.17
  • XGBRegressor: 99.15
  • RandomForestRegressor: 95.68
Then, we proceed in the process of HyperParameters Tuning, which has been performed through RandomizedSearchCV.

### Results
The results are obtained on a Train/Test split of 80/20 and cross-validated through KFold with a cv of 5, and are the following:
  • XGBRegressor: 94.78
  • RandomForestRegressor: 95.66

<hr/>

## Content-Based Recommendation System

### Model & Training
TODO

### Results
TODO

<hr/>

## Contact
Feel free to e-mail etorre@student.ethz.ch.
  
## Acknowledgements
The code in this project is adapted and modified from the following repositories:
1. [Title](https://)