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

- **Languages**:
  - Python 3.x

- **Libraries**:
  - `pandas`: Data manipulation
  - `numpy`: Numerical operations
  - `nltk`: Natural Language Processing
  - `scikit-learn`: ML algorithms (TfidfVectorizer, cosine_similarity)
  - `pickle`: Model serialization

## 📊 Dataset

- **Original dataset size**: 57,650 songs
- **Balanced dataset**: 10,000 songs
- **Features**:
  - Artist name
  - Song title
  - Lyrics text

## 🚀 Getting Started

### Prerequisites

Ensure you have Python 3.x installed. You can check your Python version using:
```bash
python --version
```

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/winter000boy/Music-Recommendation.git
   cd Music-Recommendation
   ```

2. **Create and activate a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. **Prepare the dataset**:
   Place your dataset in the `data/` directory. Ensure it is formatted as expected (CSV with columns for artist name, song title, and lyrics).

2. **Run the preprocessing script**:
   ```bash
   python preprocess.py
   ```

3. **Train the model**:
   ```bash
   python train_model.py
   ```

4. **Generate recommendations**:
   ```bash
   python recommend.py "Your song lyrics here"
   ```

### Example

To get recommendations for a song, run:
```bash
python recommend.py "Imagine there's no heaven..."
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature-branch`)
6. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔍 Keywords

- Music Recommendation System
- Lyrics Analysis
- Natural Language Processing
- TF-IDF
- Cosine Similarity
- Machine Learning
- Python
