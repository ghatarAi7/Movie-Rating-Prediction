# Movie Rating Prediction with Machine Learning

## Project Overview
This project aims to predict movie ratings (vote_average) using regression techniques. By analyzing the **TMDB 5000 Movie Dataset**, we built a model that can forecast audience reception based on movie attributes like budget, genres, and cast.

## Methodology
- **Data Preprocessing:** Merged movie and credits datasets, handled missing values.
- **Feature Engineering:** Used `CountVectorizer` to process text-based tags and metadata.
- **Model Selection:** Compared three different models:
  1. Linear Regression
  2. Random Forest Regressor
  3. **XGBoost Regressor** (The best performing model)

## Key Results
- **Top Model:** XGBoost
- **Mean Absolute Error (MAE):** 0.41
- This low MAE indicates that our model's predictions are, on average, within 0.41 points of the actual rating.

## Repository Contents
- `movie_rating_ipynb.ipynb`: Complete Python code and analysis.
- `Predicting-Movie-Ratings-with-Machine-Learning.pptx`: Detailed project presentation.
