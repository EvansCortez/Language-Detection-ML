# 🌍 Language Detection using NLP & Machine Learning

A robust Natural Language Processing (NLP) pipeline designed to identify the language of a given text. This project utilizes the **European Parliament Proceedings Parallel Corpus (Europarl)** and implements a classification model using `scikit-learn`.

---

## 📖 Overview
Language detection is a fundamental task in modern software, from search engines to content moderation. This project explores how machine learning can distinguish between 21 different European languages by analyzing character-level patterns and linguistic structures.

### Key Features:
* **Dataset:** Europarl (high-quality, professionally translated text).
* **Technique:** Character-level N-grams (bi-grams and tri-grams) to handle short text inputs.
* **Algorithm:** Logistic Regression for fast, scalable classification.
* **Serialization:** Model exported via `joblib` for easy deployment in web apps.

---

## 🛠️ Project Structure
```text
├── data/               # Raw and processed datasets
├── models/             # Serialized .joblib model files
├── src/
│   ├── preprocess.py   # Text cleaning & normalization
│   ├── train.py        # Model training & evaluation logic
│   └── predict.py      # CLI tool for real-time predictions
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
