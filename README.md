# 🎬 Movie Recommendation System

This is a **Movie Recommendation Web App** built using **Python**, **Pandas**, **Machine Learning**, and **Streamlit**. It recommends movies based on a selected movie by finding its sequels/prequels (if any) and similar genre movies sorted by average rating.

---

## 🔍 Features

- ✅ Recommends sequels and prequels (e.g., Toy Story → Toy Story 2 & 3)
- ✅ Suggests movies from similar genres based on rating
- ✅ Always returns at least 5 relevant recommendations
- ✅ Easy-to-use Streamlit web interface

---

## 🚀 Demo

> You can deploy this project using [Streamlit Cloud](https://streamlit.io/cloud) or run it locally (see below).

---

## 📦 Tech Stack

- Python
- Pandas
- Streamlit
- Machine Learning (genre similarity, average rating logic)

---

## 📁 Dataset Used

- `movies.csv` – contains movie titles and genres
- `ratings.csv` – contains user ratings for each movie

> These datasets are from the [MovieLens 100k dataset](https://grouplens.org/datasets/movielens/100k/).

---

## 🛠️ How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/Asrithkarthikeya/movie-recommender.git
cd movie-recommender
python -m streamlit run app.py
