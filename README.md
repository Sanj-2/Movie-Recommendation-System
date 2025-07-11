# 🎬 Movie Recommendation System

A content-based movie recommender system that suggests similar movies based on user input using cosine similarity on movie vectors.

---

## 🚀 Features

- Recommend movies similar to selected one
- Poster display using TMDB API
- Web UI built with Flask
- Trained vectorizer & similarity matrix for fast predictions

---

## 🧰 Tech Stack

- Python
- Pandas, Scikit-learn
- Flask
- Requests (for API)
- Pickle

---

## 📁 Files

- `app.py` – Flask backend
- `movie_list.pkl` – Movie data
- `similarity.pkl` – Pre-computed similarity matrix
- `templates/` – HTML
- `static/` – CSS
- `movie_recommender.ipynb` – Model creation & vectorization

---

## ▶️ How to Run Locally

```bash
pip install -r requirements.txt
python app.py
