# Emotion Recognition App using Deep Learning (CNNs)

## Overview
This is a simple Streamlit web application that detects six human emotions—Joy, Fear, Anger, Love, Sadness, and Surprise. It leverages machine learning and deep learning models trained on preprocessed text data.

Here’s a cleaner, well-structured rephrasing of your text:

---

## Requirements

Ensure the following packages are installed:

```bash
pip install scikit-learn==1.3.2
pip install streamlit numpy nltk
pip install tensorflow==2.15.0
```

## Usage

### Model and Files

The application relies on the following pre-trained files:

* **logistic\_regression.pkl** – Pickle file containing the logistic regression model.
* **tfidf\_vectorizer.pkl** – Pickle file containing the TF-IDF vectorizer.
* **label\_encoder.pkl** – Pickle file containing the label encoder.

### Functionality

1. Enter text into the input box.
2. Click **"Predict"** to view the predicted emotion along with its probability.





