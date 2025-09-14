# 🎧 Spotify Hybrid Recommender

A smart music recommendation system that combines the **power of content-based filtering** with the **popularity of trending tracks** — giving users suggestions that are both **relevant** and **appealing**.

---

## 🔍 Overview

This project explores and compares two approaches to building music recommendation systems using a subset of the **Spotify Tracks Dataset**:

- 🎵 **Content-Based Filtering**: Recommends songs based on similarity in audio features and genre.
- 🧠 **Hybrid Filtering**: Balances content similarity with popularity to provide smarter recommendations.

> ⚡ **Goal:** Improve recommendation **relevance**, **personalization**, and **user satisfaction** by combining content similarity with real-world popularity metrics.

---

## 📚 Project Highlights

- 🎼 **Dataset**: 15,000 sampled tracks from Spotify’s full dataset (232K+ tracks)
- 🎛 **Features Used**:
  - Categorical: `genre`, `artist_name`, `track_name`, `track_id`
  - Numerical: `popularity`, `danceability`, `energy`, `valence`, `tempo`, etc.
- 🧮 **Models Implemented**:
  - 🔍 *Content-Based Filtering* using cosine similarity
  - ⚖️ *Hybrid Filtering* using a weighted score:
    ```
    Hybrid Score = 0.7 × Content Similarity + 0.3 × Normalized Popularity
    ```

---

## 📊 Results at a Glance

| 🔬 Method          | ⭐ Avg. Popularity (Top-10) |
|-------------------|-----------------------------|
| Content-Based      | 44.18                       |
| Hybrid Filtering   | 69.9                        |

✅ **Observation**: Hybrid Filtering consistently produces recommendations that are **more popular** and **engaging** to users without sacrificing relevance.

---


