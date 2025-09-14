# Spotify Hybrid Recommender 🎵

This project explores and compares two music recommendation system approaches — **Content-Based Filtering** and **Hybrid Filtering** — using a subset of the **Spotify Tracks Dataset**. The aim is to improve recommendation **relevance**, **personalization**, and **user satisfaction** by combining audio features with popularity metrics.

## 🚀 Project Highlights
- Dataset: 15,000 sampled tracks from Spotify’s 230K+ track dataset
- Features used: genre, popularity, acousticness, energy, danceability, etc.
- Implemented Models:
  - 🔍 Content-Based Filtering (using cosine similarity)
  - ⚖️ Hybrid Filtering (70% similarity + 30% popularity)
- Evaluation: Average popularity of top-10 recommended tracks
- Results: Hybrid model yielded more relevant and widely appealing recommendations

## 📊 Results Snapshot

| Method          | Avg. Popularity (Top-10) |
|-----------------|--------------------------|
| Content-Based   | 44.18                    |
| Hybrid          | 69.9                     |

## 📁 Contents
- `notebooks/` – Jupyter notebooks for model development
- `data/` – Processed dataset subset (15K tracks)
- `poster/` – Two-page academic poster (PDF)
- `README.md` – Project overview and setup instructions

## 🛠️ Technologies Used
- Python, Pandas, NumPy, Scikit-learn
- Matplotlib, Seaborn
- Cosine Similarity
- Data Normalization

## 📌 Conclusion
Combining **acoustic features** with **popularity scores** results in more engaging and effective music recommendations. The hybrid model is a practical step toward smarter recommendation systems.

## 🧠 Future Work
- Incorporate collaborative filtering for deeper personalization
- Build a simple web app demo (e.g., using Streamlit)

## 📜 License
MIT License

