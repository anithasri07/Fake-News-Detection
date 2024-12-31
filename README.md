# Fake-News-Detection
A machine learning project for detecting fake news using the Kaggle dataset. It features data preprocessing, Bag-of-Words, n-grams, and models like Random Forest, KNN, and Naive Bayes. Includes performance analysis using precision, recall, and F1-score. Explore NLP and enhance results!
# Fake News Detection

This repository contains a project focused on detecting fake news using machine learning and natural language processing (NLP) techniques. The dataset used for this project is sourced from [Kaggle's Fake News Content Detection dataset](https://www.kaggle.com/datasets/anmolkumar/fake-news-content-detection?select=test.csv).

## Features
- **Data Preprocessing**: Cleans and tokenizes raw text data, including stopword removal and lemmatization.
- **Feature Extraction**: Uses techniques like Bag-of-Words (BoW), TF-IDF, and n-grams.
- **Machine Learning Models**:
  - Random Forest
  - K-Nearest Neighbors (KNN)
  - Multinomial Naive Bayes
- **Evaluation Metrics**: Precision, recall, F1-score, and accuracy.
- **Analysis**: Investigates the impact of feature selection, preprocessing, and distance metrics on model performance.

---

## Dataset
The dataset used is from Kaggle: [Fake News Content Detection](https://www.kaggle.com/datasets/anmolkumar/fake-news-content-detection?select=test.csv).

The dataset contains:
- **Train.csv**: Training data for the models.
- **Test.csv**: Data for evaluating the model performance.

---

## Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Required Python libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `nltk`
  - `matplotlib`
