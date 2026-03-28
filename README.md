# Recommender System Project

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Polenoz/Recommender-Systems/blob/main/Recommender_Systems.ipynb)

This repository reproduces the Recommender Systems exercise from the course `Python für Data Science, Maschinelles Lernen & Visualization` for `Prüfungsaufgabe 1`.

## Overview

This project demonstrates how to build a simple movie recommender system using user rating data. The notebook includes data loading, exploration, collaborative filtering, and movie similarity analysis to suggest related movies.

## Contents

- `Recommender_Systems.ipynb`: Jupyter notebook with the full workflow
- `U.data`: User rating dataset
- `Movie_Id_Titles`: Movie title dataset
- `requirements.txt`: List of required Python packages

## Dataset

The datasets (`U.data` and `Movie_Id_Titles`) contain user ratings and movie titles for the recommender system example. They are loaded directly from the repository when running the notebook.

## How to Run

### Google Colab (Recommended)

1. Click the **Open in Colab** badge above.
2. The notebook will open in Google Colab.
3. Run all cells from top to bottom in order.
4. No manual data upload is required.

### Local (Jupyter)

1. Clone or download this repository.
2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook with Jupyter:

```bash
jupyter notebook Recommender_Systems.ipynb
```

4. Run all cells from top to bottom.

## Expected Results

The notebook should reproduce the recommender systems example and show:

- data exploration and visualizations of movie ratings
- creation of a user-movie matrix
- correlation-based movie recommendations
- lists of similar movies based on collaborative filtering

Example output:

```text
Correlation    num of ratings
title
Star Wars (1977)                            1.000000    584
Empire Strikes Back, The (1980)             0.748353    368
Return of the Jedi (1983)                   0.672556    507
Raiders of the Lost Ark (1981)              0.536117    420
Austin Powers: International Man of Mystery 0.377433    130
```

## Notes

This repository is intended as one of the required exercise repositories for `Prüfungsaufgabe 1`.
