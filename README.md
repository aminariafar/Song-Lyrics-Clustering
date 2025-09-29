# 🎵 Song Lyrics Clustering with NLP Embeddings

This project explores **natural language processing (NLP)** and **unsupervised learning** techniques by clustering song lyrics.  
Using text embeddings and dimensionality reduction, it demonstrates how different clustering algorithms group lyrical content into meaningful clusters.

---

## ✨ Key Contents

### Notebook
- **`lyrics_analysis.ipynb`**  
  Organized into stages:  
  - **Preprocessing & Feature Extraction** — text cleaning, stemming, lemmatization  
  - **Embedding** — Sentence-BERT embeddings for lyrics  
  - **Dimensionality Reduction** — PCA applied to embeddings for visualization and clustering  
  - **Clustering Methods**:  
    - **KMeans** — with silhouette score evaluation and cluster sampling  
    - **DBSCAN** — density-based clustering with neighbor analysis  
    - **Hierarchical Clustering** — dendrogram visualization and flat cluster extraction  
  - **Visualization** — 2D plots of clustered lyrics, sampling examples

### Dataset
- **`musicLyrics.csv`** — dataset of raw lyrics used for analysis.  

---

## 🧱 Project Structure
```
Song-Lyrics-Clustering-main/
├── lyrics_analysis.ipynb   # Jupyter notebook (NLP preprocessing, embeddings, clustering)
└── musicLyrics.csv         # Dataset of song lyrics
```

---

## 🎯 Educational Context
This project was developed as an **NLP and machine learning experiment**, focusing on:  
- How embeddings capture lyrical semantics  
- How clustering groups similar songs without labels  
- Visualizing and evaluating clustering quality with silhouette scores  

It serves as a hands-on example of applying **unsupervised learning** to real-world text data.

---

📚 Made for research & learning — combining music lyrics, embeddings, and clustering to uncover hidden structure in text.
