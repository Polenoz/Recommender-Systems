# Recommender System Project

In this project, a simple movie recommendation system is created using user rating data. The system suggests similar movies based on how users rated different films.

## Dataset

The project uses the following files:

* U.data
* Movie_Id_Titles

These files should be in the same directory as the notebook.

## How to run

You can run the notebook using Google Colab:

* Open the notebook
* Upload the dataset files
* Run all cells

You can also run it locally:

* Install the required libraries (pandas, numpy, matplotlib, seaborn)
* Open the notebook with Jupyter
* Run all cells

## What is done in this notebook

* The dataset is loaded and prepared
* User ratings are combined with movie titles
* A user-item matrix is created
* Similarities between movies are calculated
* Movie recommendations are generated based on correlations

## Evaluation

The recommendation system is based on correlation between user ratings.
Movies that have similar rating patterns are considered similar.
