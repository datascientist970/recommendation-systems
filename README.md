# Recommendation Systems

Two classic recommender-system notebooks: a **book recommender** (popularity-based + collaborative filtering with cosine similarity) and a **movie recommender** (content-based similarity on MovieLens-style data).

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)

## Overview

## Origin

This project was originally developed inside the `Data-Science` notebook collection and now lives in its own repository for easier discovery and use.

Together the notebooks cover the three foundational recommender approaches — popularity, collaborative filtering and content-based similarity.

## Notebooks

| Notebook | System | Technique | Data expected |
|---|---|---|---|
| `book_recommendation.ipynb` | Book recommendations (Book-Crossing style data) | Popularity-based ranking, then user–item pivot + `cosine_similarity` collaborative filtering; model saved with pickle | `Books.csv`, `Ratings.csv` (not included) |
| `movie_recommendation.ipynb` | Movie recommendations | Cosine-similarity over movie metadata | `movie/ratings_small.csv`, `movie/movies_metadata.csv` (not included) |

## Getting Started

```bash
git clone https://github.com/datascientist970/recommendation-systems.git
cd recommendation-systems
pip install -r requirements.txt
jupyter notebook
```

Download the datasets (Book-Crossing / MovieLens metadata) and place them at the paths shown above before running.

## Tech Stack

Python · Pandas · NumPy · scikit-learn · Matplotlib

## Author

**Muhammad Dawood** — AI & Data Science Engineer
GitHub: https://github.com/datascientist970 · LinkedIn: https://www.linkedin.com/in/dawood406/
Mardan, Khyber Pakhtunkhwa, Pakistan
