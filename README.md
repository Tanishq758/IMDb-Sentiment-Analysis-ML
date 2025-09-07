# IMDb Movie Review Sentiment Analysis

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.2-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

This project performs **sentiment analysis** on movie reviews from the [IMDb Large Movie Review Dataset](https://ai.stanford.edu/~amaas/data/sentiment/). The goal is to classify reviews as **positive** or **negative** using **machine learning models**.

---

## Dataset

- **Source:** [IMDb Large Movie Review Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)
- **Size:** 50,000 reviews (25,000 positive, 25,000 negative)
- **Split:** Train (25,000), Test (25,000)
- **Format:** Text files organized in `pos` and `neg` directories
- **Labels:** 0 = Negative, 1 = Positive

---

## Preprocessing

Text preprocessing includes:

- Lowercasing
- Removing HTML tags
- Removing URLs
- Removing numbers and punctuation
- Removing extra whitespace

---

## Feature Extraction

- **Method:** TF-IDF Vectorization
- **Max Features:** 20,000
- **Stop Words:** English

---

## Models Implemented

1. **Logistic Regression**
2. **Multinomial Naive Bayes**
3. **Linear Support Vector Machine (SVM)**

Each model is trained on TF-IDF features and evaluated using:

- Accuracy
- F1 Score
- Classification Report

---

## Example Results

| Model                 | Accuracy | F1 Score |
|-----------------------|----------|----------|
| Logistic Regression   | 89%      | 89%      |
| Naive Bayes           | 86%      | 85%      |
| Linear SVM            | 88%      | 88%      |

> Results may vary depending on train-test split and random seed.

---

## Usage

1. Clone the repository:
```bash
git clone <repository_url>
