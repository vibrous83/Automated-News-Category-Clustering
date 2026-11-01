# Automated-News-Category-Clustering
This project aims to automatically group news articles based on topic similarity using the K-Means Clustering algorithm.

## Insight:
- Preprocessed 2,406 news articles using tokenization, stopword removal, lemmatization, and entity merging for location (GPE) and organization (ORG) names.
- Integrating TF-IDF with Truncated SVD effectively reduces noise and optimizes computation speed without losing key topic variations.
- Evaluating model performance via Silhouette Score provides an objective way to determine the optimal number of distinct clusters.

## Outcome: 
Successfully grouped 2,406 news articles into 3 optimal clusters with a Silhouette Score of 0.2718, representing distinct categories: Politics, Technology, and General News.

## Link:
https://colab.research.google.com/drive/17gRo5dCuXdyedA0z_30d0CtVIsuzOYQh?usp=sharing
