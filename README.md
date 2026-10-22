# Music Clustering and Content-Based Recommendation System

## Project Overview
This project analyzes music data using **Databricks and Apache Spark**. It applies machine learning techniques to identify patterns in audio features and build a content-based music recommendation system.

## Technologies
- Databricks
- PySpark and Spark MLlib
- Spark SQL
- KMeans Clustering
- Principal Component Analysis (PCA)
- Cosine Similarity

## Methodology
1. **Data Preprocessing:** Convert audio features to numerical types and handle missing or malformed values.
2. **Exploratory Data Analysis:** Use Spark SQL to analyze music characteristics and compare feature distributions across clusters.
3. **Feature Engineering:** Assemble and standardize audio features for machine learning.
4. **KMeans Clustering:** Group songs based on similarities in their audio characteristics.
5. **PCA Visualization:** Reduce feature dimensions to visualize cluster patterns.
6. **Music Recommendation:** Recommend similar songs using cosine similarity and cluster-based filtering.

## Key Results
- Processed **170,653 song records**, retaining **169,777 records** after cleaning.
- Identified six clusters of songs with different audio characteristics.
- Visualized clustering patterns using PCA.
- Built a content-based recommendation function to retrieve acoustically similar songs.

## Author
**JING TAN**
