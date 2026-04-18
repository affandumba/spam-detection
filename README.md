# Spam Detection

## Problem Statement
Classify messages as Ham (legitimate) or Spam using Natural Language Processing and Machine Learning.

## Dataset
- SMS Spam Collection Dataset (UCI Machine Learning Repository)
- 5572 messages — 4825 Ham, 747 Spam
- Loaded directly from URL — no download needed

## NLP Pipeline
- Lowercasing
- Removing special characters
- Stopword removal
- Lemmatization
- TF-IDF Vectorization with bigrams

## Model Used
- Multinomial Naive Bayes

## Highlights
- EDA with class distribution and message length analysis
- Correct TF-IDF usage — fit on train only to prevent data leakage
- Confusion Matrix + Precision, Recall, F1-Score
- 5-Fold Cross Validation
- Live prediction on example messages

## Result
| Metric | Score |
|---|---|
| Test Accuracy | ~98% |
| Cross Validation | ~97% |

## Tools & Libraries
Python, NumPy, Pandas, Scikit-learn, NLTK, Matplotlib, Seaborn
