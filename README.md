# IMDB Movie Reviews Sentiment Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-orange)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-brightgreen)
![BoW](https://img.shields.io/badge/Feature%20Extraction-Bag%20of%20Words-blueviolet)
![TF-IDF](https://img.shields.io/badge/Feature%20Extraction-TF--IDF-critical)
![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange)
![Colab](https://img.shields.io/badge/Run%20on-Google%20Colab-yellow)
![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
<!-- ![Status](https://img.shields.io/badge/Project-In%20Progress-yellow) -->

A Natural Language Processing (NLP) project that performs sentiment analysis on IMDB movie reviews using the Bag of Words (BoW) approach and Term Frequency-Inverse Document Frequency (TF-IDF).

---

## Project Overview

This project classifies IMDB movie reviews as Positive or Negative by:
- Cleaning raw text data
- Converting text into numerical features using BoW and TF-IDF
- Training machine learning classifiers
- Evaluating performance using standard metrics

---

## Dataset

- Source: IMDB Movie Reviews Dataset
- Provider: Kaggle
- Link: [https://www.kaggle.com/datasets/vishakhdapat/imdb-movie-reviews](https://www.kaggle.com/datasets/vishakhdapat/imdb-movie-reviews)
- Total Reviews: 50,000
- Labels: Positive / Negative

Dataset is downloaded programmatically using KaggleHub.

```bash
import kagglehub
path = kagglehub.dataset_download("vishakhdapat/imdb-movie-reviews")
```

---

## Approach

- Text Preprocessing
    - Lowercasing
    - Removing HTML tags
    - Stopword removal
- Feature Extraction
    - Bag of Words (BoW)
    - TF-IDF
- Model Training
    - Logistic Regression
    - Naive Bayes
    - SVM
- Evaluation
    - Accuracy
    - Confusion Matrix

---

## Results


### Using BoW

| Model               | Accuracy |
|---------------------|----------|
| Naive Bayes         | 67.23%   |
| Linear SVC          | 69.34%   |
| Logistic Regression | 69.43%   |


### Using TF-IDF

| Model               | Accuracy |
|---------------------|----------|
| Naive Bayes         | 67.56%   |
| Linear SVC          | 69.56%   |
| Logistic Regression | 70.00%   |

---

## Future Improvements

- Try Word2Vec / GloVe
- Apply Deep Learning (LSTM)

---

## Contributing

Contributions, issues, and feature requests are welcome!