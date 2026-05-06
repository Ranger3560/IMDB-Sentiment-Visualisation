# IMDB-Sentiment-Visualisation
# Sentiment Analysis on Movie Reviews

This project builds a machine learning model to classify movie reviews as positive or negative using natural language processing (NLP) techniques.

---

## Overview

The goal is to automatically analyze text reviews and predict sentiment. The pipeline includes:

* Text preprocessing
* Feature extraction using TF-IDF
* Model training using Logistic Regression
* Evaluation with standard metrics
* Visualizations for insights

---

## Tech Stack

* Python
* pandas
* scikit-learn
* matplotlib
* seaborn
* wordcloud

---

## Dataset

The dataset consists of:

* `review`: Text of the movie review
* `sentiment`: Label (`positive` or `negative`)

---

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/sentiment-analysis.git
cd sentiment-analysis
pip install -r requirements.txt
```

---

## Usage

### 1. Train the Model

```bash
python train.py
```

### 2. Predict on Test Data

```bash
python predict.py
```

Predictions will be saved as:

```
predictions.csv
```



## Visualizations

The project includes several visualizations:

* Sentiment distribution (class balance)
* Word clouds for positive and negative reviews
* Top important words from the model
* Confusion matrix
* Review length distribution


## Model Pipeline

1. Text cleaning (lowercasing, removing noise)
2. TF-IDF vectorization
3. Logistic Regression classifier


## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score



##  Example Predictions

| Review                     | Predicted Sentiment |
| -------------------------- | ------------------- |
| "Amazing movie, loved it!" | Positive            |
| "Terrible and boring..."   | Negative            |


## Future Improvements

* Use advanced models like BERT
* Hyperparameter tuning
* Deploy as a web app (Flask/Streamlit)
* Add more preprocessing (stopwords, lemmatization)



## Acknowledgements

* Open datasets for sentiment analysis
* NLP community and open-source contributors

---
