# Music Clustering and Content-Based Recommendation System

## Project Overview
This project analyzes Spotify music data using **Databricks and Apache Spark**. It applies machine learning techniques to identify patterns in audio features and build a content-based music recommendation system.

## Dataset
- **Name:** Spotify Dataset 1921–2020, 160k+ Tracks
- **Source:** [Kaggle – Spotify Dataset 1921–2020, 160k+ Tracks](https://www.kaggle.com/datasets/yamaerenay/spotify-dataset-1920-2020-160k-tracks)
- **Original records:** 170,653 songs
- **Features:** Audio characteristics, song titles, artists, release years, and popularity.

## Technologies
- Databricks
- PySpark and Spark MLlib
- Spark SQL
- KMeans Clustering
- Principal Component Analysis (PCA)
- Cosine Similarity

## Methodology
1. **Data Preprocessing:** Convert audio features to numerical types and handle missing or malformed values.
2. **Exploratory Data Analysis:** Use Spark SQL to investigate music characteristics and compare audio features across clusters.
3. **Feature Engineering:** Assemble and standardize audio features for machine learning.
4. **KMeans Clustering:** Group songs according to similarities in their audio characteristics.
5. **PCA Visualization:** Reduce feature dimensions to visualize clustering patterns.
6. **Music Recommendation:** Recommend acoustically similar songs using cosine similarity and cluster-based filtering.

## Key Results
- Retained **169,777 records** after data cleaning.
- Identified six clusters with different audio characteristics.
- Visualized cluster patterns using PCA.
- Implemented a content-based recommendation function to retrieve similar songs.

## Author
**JING TAN**
