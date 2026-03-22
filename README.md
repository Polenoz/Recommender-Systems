
# Recommender System Project

**Note:** This project was developed and tested primarily in **Google Colab**. All instructions and code are fully compatible with Colab, and the recommended way to run and reproduce results is via the Colab badge below.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Polenoz/Recommender-Systems/blob/main/Recommender_Systems.ipynb)

## Overview
This project demonstrates how to build a simple movie recommender system using user rating data. The notebook includes data loading, exploration, and collaborative filtering to suggest similar movies.

## Contents
- `Recommender_Systems.ipynb`: Jupyter/Colab notebook with the full workflow
- `U.data`, `Movie_Id_Titles`: Datasets used for recommendations
- `requirements.txt`: List of required Python packages

## Dataset
The datasets (`U.data`, `Movie_Id_Titles`) are loaded automatically from the repository when running in Colab.

## How to Run

### Google Colab (Recommended)
1. Click the **Open in Colab** badge above.
2. The notebook will open in Google Colab.
3. Run all cells from top to bottom. The datasets load automatically from the repository.
4. No manual data upload or extra setup is required.

### Local (Jupyter, also possible)
1. Clone or download this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook with Jupyter: `jupyter notebook Recommender_Systems.ipynb`
4. Run all cells.

## Expected Results
- Data exploration and visualizations of movie ratings
- Movie recommendations based on collaborative filtering
- Example output:

```

Correlation	num of ratings
title		
Star Wars (1977)	1.000000	584
Empire Strikes Back, The (1980)	0.748353	368
Return of the Jedi (1983)	0.672556	507
Raiders of the Lost Ark (1981)	0.536117	420
Austin Powers: International Man of Mystery (1997)	0.377433	130

...
```


```bash
pip install pandas numpy matplotlib seaborn jupyter
