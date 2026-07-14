<div align="center">

# Spotify Songs Recommendation System

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=28&pause=1500&color=1DB954&center=true&vCenter=true&width=900&lines=Content-Based+Music+Recommendation+System;Built+with+Machine+Learning;Powered+by+K-Nearest+Neighbors+and+Streamlit" />

<br>

<img src="https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Scikit--Learn-KNN-F7931E?style=for-the-badge&logo=scikitlearn">
<img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas">
<img src="https://img.shields.io/badge/Streamlit-Web%20Application-FF4B4B?style=for-the-badge&logo=streamlit">
<img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">

</div>

---

## Overview

The Spotify Songs Recommendation System is a **content-based recommendation engine** that suggests songs based on their audio characteristics instead of popularity or genre alone.

Using Spotify's audio features and the **K-Nearest Neighbors (KNN)** algorithm, the system identifies songs with similar musical patterns, allowing users to discover tracks that closely match their listening preferences.

---

## Features

- Content-based recommendation engine
- Machine Learning powered similarity search
- Interactive Streamlit application
- Feature scaling using StandardScaler
- Fast song recommendations using KNN
- Clean and intuitive user interface

---

## Technology Stack

| Category | Tools |
|----------|------|
| Language | Python |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib |
| Machine Learning | Scikit-learn |
| Deployment | Streamlit |
| Model Storage | Pickle |

---

## Dataset

The recommendation model utilizes Spotify's audio feature dataset.

Key attributes include:

| Feature | Description |
|----------|-------------|
| Danceability | Suitability of a track for dancing |
| Energy | Intensity and activity level |
| Loudness | Overall volume of the song |
| Speechiness | Presence of spoken words |
| Acousticness | Confidence measure of acoustic nature |
| Instrumentalness | Predicts absence of vocals |
| Liveness | Detects audience presence |
| Valence | Musical positivity |
| Tempo | Speed of the song |

---

## Project Workflow

```text
Spotify Dataset
       │
       ▼
Data Cleaning
       │
       ▼
Feature Selection
       │
       ▼
Feature Scaling
       │
       ▼
K-Nearest Neighbors Model
       │
       ▼
Recommendation Engine
       │
       ▼
Streamlit Web Application
```

---

## Machine Learning Pipeline

```text
Dataset
   │
   ▼
Preprocessing
   │
   ▼
Feature Engineering
   │
   ▼
StandardScaler
   │
   ▼
KNN Model Training
   │
   ▼
Similarity Search
   │
   ▼
Song Recommendations
```

---

## Repository Structure

```text
Spotify-Songs-Recommendation-System
│
├── data
│   └── spotify-tracks-dataset-detailed.csv
│
├── notebooks
│   └── Spotify_Songs_Recommendation_System.ipynb
│
├── models
│   ├── spotify_knn_model.pkl
│   ├── spotify_scaler.pkl
│   ├── spotify_dataset.pkl
│   └── song_indices.pkl
│
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Spotify-Songs-Recommendation-System.git
```

Navigate to the project directory

```bash
cd Spotify-Songs-Recommendation-System
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

## Future Enhancements

- Spotify API integration
- Playlist recommendations
- Mood-based recommendations
- Genre filtering
- Hybrid recommendation system
- Cloud deployment

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Machine Learning
- Recommendation Systems
- Model Serialization
- Streamlit Deployment

---

## Author

**Diksha Pandey**

Aspiring Data Analyst

GitHub: https://github.com/databydiksha

---

<div align="center">

</div>
