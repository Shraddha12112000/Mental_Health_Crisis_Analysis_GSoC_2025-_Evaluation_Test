# Mental_Health_Crisis_Analysis_GSoC_2025-_Evaluation_Test
# 🧠 Mental Health Crisis Analysis (GSoC 2025)

This project is part of the evaluation for the GSoC 2025 proposal under **AI-Powered Behavioral Analysis for Suicide Prevention, Substance Use, and Mental Health Crisis Detection**.

## 📌 Objectives

- Extract Reddit posts related to mental health crises.
- Perform sentiment and risk classification using NLP.
- Visualize crisis discussions geospatially.

---

## 🔍 Task Overview

### ✅ Task 1: Social Media Data Extraction & Preprocessing
- Extracted 150+ Reddit posts using PRAW API.
- Filtered based on 15 crisis-related keywords.
- Cleaned the text (removal of stopwords, emojis, and special characters).

### ✅ Task 2: Sentiment and Crisis Risk Classification
- Applied VADER sentiment analysis.
- Assigned risk levels based on sentiment polarity.

### ✅ Task 3: Geospatial Mapping
- Visualized discussion hotspots using a heatmap (Folium + Geocoding).

---

## 📂 Repository Structure
Mental_Health_Crisis_Analysis/ ├── data/ # Cleaned dataset ├── notebook/ # All Jupyter notebooks ├── images/ # Heatmaps or visuals ├── requirements.txt # All dependencies └── README.md # Documentation


