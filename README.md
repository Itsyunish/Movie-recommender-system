# 🎬 Movie Recommender System

This is a **content-based movie recommendation system** built using Python and Streamlit. The system suggests movies similar to the one selected by the user based on movie metadata such as genre, overview, keywords, and cast.

---

## 🔍 Features

- Recommends top 5 similar movies to the one selected
- Fetches and displays movie posters using the TMDB API
- Built with `scikit-learn`, `pandas`, and `Streamlit`
- Interactive and user-friendly web UI

---

## 🧠 How It Works

- Uses **TF-IDF Vectorization** to extract features from movie overviews
- Computes **cosine similarity** between all movies
- When a movie is selected, it returns the most similar movies based on content

---



