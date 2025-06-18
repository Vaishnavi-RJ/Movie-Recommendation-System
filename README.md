# Movie-Recommendation-System

# 🎬 Content-Based Movie Recommender System

This repository contains a content-based movie recommender system built using metadata such as movie overviews and genres. The system utilizes **TF-IDF Vectorization** and **cosine similarity** to recommend movies similar to a selected title.

## 📌 Features

- Content-based filtering using movie metadata
- TF-IDF Vectorization on movie overviews
- Cosine similarity to compute similarity scores between movies
- Returns top-N similar movies based on selected input
- Simple and easy to extend or integrate with other systems

## 📁 Dataset

The dataset used in this project is typically the [TMDb 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata), which contains:
- Movie titles
- Overviews
- Genres
- Additional metadata like cast, crew, keywords (optional)

> You can download the dataset from Kaggle and place it in the project directory as `movies_metadata.csv`.

## ⚙️ How It Works

1. **Data Cleaning & Preprocessing**
   - Load the dataset and handle missing values.
   - Select and process relevant fields such as `overview` and `genres`.

2. **TF-IDF Vectorization**
   - Convert the movie overviews into numerical vectors using **TF-IDF** to emphasize important terms.

3. **Cosine Similarity Calculation**
   - Compute the cosine similarity between all movie vectors.
   - Use similarity scores to recommend the most similar movies.

4. **Recommendation Function**
   - A function takes a movie title as input and returns a list of similar titles.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn (TF-IDF, Cosine Similarity)
- Jupyter Notebook (for development)


