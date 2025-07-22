# 🎬 Movie Recommendation System (Content-Based)

## 📌 Aim:

To build a content-based movie recommendation system that suggests similar movies based on the user's selected movie, using NLP techniques and cosine similarity.

---

## 📦 Requirements:

- Python 3.x
- pandas
- numpy
- scikit-learn
- nltk
- streamlit
- requests
- pickle

## 📝 Description:

This project uses metadata of movies (such as genres, overview, keywords, cast, and crew) to recommend similar movies. The core idea is to represent each movie using a textual feature vector and compute the similarity between movies using **cosine similarity**.

The following key techniques are used:

- **Natural Language Processing (NLP)**: Used for text preprocessing, tokenization, and stemming using `nltk.stem.porter.PorterStemmer`.
- **Vectorization**: Implemented using `CountVectorizer` from Scikit-learn to convert text into numerical form.
- **Cosine Similarity**: Calculates similarity scores between movies based on vectorized tags.
- **Data Preprocessing**: Performed using `pandas` and `ast` to extract and clean JSON-style data from columns like cast, crew, genres, etc.
- **Frontend Interface**: Built using **Streamlit**, allowing users to interactively select a movie and view poster-based recommendations.
- **TMDB API**: Used to fetch movie posters dynamically for a better visual experience.

---

## Kaggle Dataset:

link=https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv

## Output:
![app code](https://github.com/user-attachments/assets/c8e6d304-f263-42d5-91e1-dd1aa8ef4258)

![Output 1](https://github.com/user-attachments/assets/bf88edc2-08c8-47ee-bfce-e8143a2d17ec)

![Output 2](https://github.com/user-attachments/assets/2ada0d22-818c-4dba-86f1-29d4521f2de4)

