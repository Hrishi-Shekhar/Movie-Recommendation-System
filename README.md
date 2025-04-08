# 🎬 Movie Recommendation System

This project is a **content-based movie recommendation system** that suggests movies based on user input using cosine similarity. It analyzes features like genres, keywords, and more to find and recommend similar movies.

## 🔍 Features

- Content-based filtering using cosine similarity
- Analyzes movie metadata (genres, keywords, etc.)
- Returns top similar movies based on a given input
- Built with Python and popular data science libraries

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn

## 📊 How It Works

1. Load and clean the movie dataset.
2. Combine relevant movie features into a single string (e.g., title, genres, keywords).
3. Convert this data into vectors using `CountVectorizer`.
4. Calculate cosine similarity between all movies.
5. Take a movie title as input and return the most similar movies.
