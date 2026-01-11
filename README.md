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
###  Conclusion
Emotion Recognition App using NLP & Deep Learning | Self Project

(Deep Learning • NLP • Text Classification)

Built a multi-class emotion classifier using TF-IDF with Logistic Regression, SVM, and Random Forest, achieving 82–85% accuracy across 6 emotions.

Developed an LSTM-based deep learning model for sequence learning, generating high-confidence predictions (≈0.95–0.99) on unseen text.

Implemented an end-to-end inference pipeline with saved models (pickle/H5) for real-time emotion prediction.






