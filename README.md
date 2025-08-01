
### 🎧 Spotify Song Classification for Playlist Curation
This project classifies Spotify songs into distinct musical categories using unsupervised machine learning. By analyzing key audio features (e.g., energy, danceability, tempo), we grouped tracks into clusters that can power personalized playlists, help users discover new music, and support music-tech applications.

### Objectives
1.Cluster songs based on their audio characteristics

2.Label and interpret each group (e.g., Calm, Dance, Acoustic)

3.Build a Streamlit app that classifies songs based on user input

4.Recommend 3 songs from each cluster as sample playlists

### 🎵 Dataset Overview
Source: Spotify Audio Features Dataset
Features: danceability, energy, valence, tempo, acousticness, speechiness, instrumentalness, etc.


### 🧠 Methodology
1. Clustering Algorithms
 - K-Means Clustering
 - Hierarchical Clustering


###  Deployment using Streamlit App
Inputs: Audio features (via sliders/form)
Outputs: Predicted cluster label + sample song recommendations

Backend: joblib-saved scaler & clustering model


streamlit run app.py



---

## Project Structure
📦 Spotify Song Classification
├── app.py
├── clustering_model.pkl
├── scaler.pkl
├── pca.pkl
├── Spotify Dataset.csv
├── notebooks/
│   └── Clustering_EDA_Modeling.ipynb
└── README.md
