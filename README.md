# movie_revenue_predictor
A data analysis and machine learning project that predicts movie revenue based on various features from the TMDB dataset.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [EDA & Insights](#eda--insights)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Contact](#contact)

---

## Overview

The goal of this project is to build a machine learning model that predicts the revenue of a movie based on available metadata like budget, cast, runtime, genres, etc. This project demonstrates the end-to-end data pipeline from data cleaning to deployment-ready modeling.

---

## Dataset

- **Source**: [TMDB (The Movie Database)](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- **Rows**: ~5,000 movies
- **Columns**: 20+ features such as `budget`, `genres`, `release_date`, `runtime`, etc.

---

## EDA & Insights

- Budget and revenue are highly skewed, hence log-transformed.
- budget shows strong correlation with revenue while runtime and release year show weak correlation with revenue.

---

## Data Preprocessing

- Removed duplicates and missing values
- Log-transformed skewed features
- One-hot encoded categorical variables (genres, production companies, etc.)

## Modeling

- Tried **Linear Regression**
- Evaluation metrics:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score

---

## Results
- MAE : 1.01
- MSE : 2.21
- R² : 0.56



---

## Technologies Used

- **Python**
- **Pandas, NumPy, Matplotlib, Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**
- **Joblib** for model saving

---

## Contact
**Manali Gohil** 
[LinkedIn](https://www.linkedin.com/in/manaligohil06/) | [Email](mailto:manaligohil06@email.com)
