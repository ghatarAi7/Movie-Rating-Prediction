# Movie Rating Prediction with Machine Learning
#Project Overview
This project was developed as part of the Machine Learning course. The primary goal is to predict movie ratings (vote average) by leveraging the TMDB 5000 Movie Dataset. By analyzing various movie attributes such as budget, revenue, genres, keywords, cast, and crew, we built and evaluated multiple regression models to forecast audience reception.

Team Members
Ghatar Butti Alqhtani

Abdullah Saad Al-Qarni

Supervised by: Dr. Ali Falih Al-Shahrani

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

#Dataset: The data used in this project is the TMDB 5000 Movie Dataset available on Kaggle.
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata
