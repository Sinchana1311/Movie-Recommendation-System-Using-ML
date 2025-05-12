# 🎬 Movie Recommendation System

This project is a content-based Movie Recommendation System built with **Python**, **Pandas**, **Scikit-learn**, and deployed using **Streamlit**.

It recommends similar movies or TV shows based on the metadata such as director, cast, genres, and description.

## 📁 Files

- `app.py` – Streamlit web app to run the recommender
- `movie_dataset.pkl` – Preprocessed movie data
- `similarity.pkl` – Cosine similarity matrix
- `requirements.txt` – List of required Python packages

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/movie-recommender.git
cd movie-recommender
```

2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Run the Streamlit app:

```bash
streamlit run app.py
```

## ✅ Features

- Searchable dropdown to select a movie
- Displays top 5 similar movies with similarity score
- Based on textual metadata similarity using CountVectorizer & Cosine Similarity

## 📌 Example

Select **"Ganglands"** and click **"Recommend"** to get similar shows.

---

🛠 Built with love using **Python**, **Streamlit**, and **Machine Learning**.
