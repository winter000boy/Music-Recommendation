# 🎵 Lyrics-Based Music Recommendation System

A machine learning-based song recommendation system that suggests similar songs based on lyrical content analysis using Natural Language Processing (NLP) techniques.

## 🎯 Overview

This project implements a content-based recommendation system that analyzes song lyrics to find similar songs. It uses TF-IDF vectorization and cosine similarity to measure the semantic similarity between songs.

## ⚙️ Technical Implementation

- **Data Processing**: 
  - Cleaned and preprocessed lyrics data
  - Implemented text tokenization
  - Applied Porter Stemming for root word extraction
  - Removed stopwords and special characters

- **Feature Engineering**:
  - TF-IDF (Term Frequency-Inverse Document Frequency) Vectorization
  - Cosine Similarity Matrix computation
  - Dimensionality: 10,000 songs × 26,031 features

## 🛠️ Technologies Used

- Python 3.x
- Libraries:
  - pandas: Data manipulation
  - numpy: Numerical operations
  - nltk: Natural Language Processing
  - scikit-learn: ML algorithms (TfidfVectorizer, cosine_similarity)
  - pickle: Model serialization

## 📊 Dataset

- Original dataset size: 57,650 songs
- Balanced dataset: 10,000 songs
- Features:
  - Artist name
  - Song title
  - Lyrics text

## 🚀 Getting Started

1. Clone the repository
```bash
git clone https://github.com/winter000boy/music-recommendation-system.git