# 📝 NLP Text Classifier

> End-to-end text classification pipeline with NLP preprocessing and supervised learning

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![NLTK](https://img.shields.io/badge/NLTK-154f3c?style=flat-square)](https://nltk.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org)

*IronHack AI Engineering Bootcamp — NLP Project*

---

## 📌 Overview

A complete text classification pipeline built from the ground up — covering every stage from raw text ingestion through to a trained and evaluated model. Demonstrates core NLP principles: how unstructured text becomes structured numerical features, and how those features power accurate classification.

---

## ✨ Features

- 🔤 **Text Preprocessing** — cleaning, normalisation, tokenisation, stopword removal, lemmatisation
- 📐 **Feature Extraction** — Bag of Words and TF-IDF compared side by side
- 🤖 **Multiple Classifiers** — Logistic Regression, Naive Bayes, and SVM evaluated
- 📊 **Evaluation Suite** — accuracy, precision, recall, F1-score, confusion matrix
- 🔍 **Error Analysis** — inspection of misclassified samples

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Language | Python |
| Data Processing | Pandas, NumPy |
| NLP | NLTK |
| Feature Extraction | Scikit-learn (CountVectorizer, TF-IDF) |
| Modelling | Scikit-learn (Logistic Regression, Naive Bayes, SVM) |
| Evaluation | Scikit-learn metrics, Matplotlib, Seaborn |
| Notebook | Jupyter |

---

## 🔍 Pipeline

```
Raw Text → Cleaning → Tokenisation → Stopword Removal → Lemmatisation
  → Vectorisation (BoW / TF-IDF) → Model Training → Evaluation
```

---

## 🚀 Getting Started

```bash
git clone https://github.com/Marvin2798/nlp_project.git
cd nlp_project
pip install pandas numpy scikit-learn nltk matplotlib seaborn jupyter
jupyter notebook
```

---

## 🔮 Future Improvements

- [ ] Add n-gram features to capture phrase-level context
- [ ] Implement word embeddings (Word2Vec / GloVe)
- [ ] Fine-tune hyperparameters with GridSearchCV
- [ ] Package pipeline with a predict() function for new inputs

---

## 👤 Author

**Marvin Mends** — [@Marvin2798](https://github.com/Marvin2798)

---

<div align="center">

⭐ Star this repo if you found it useful!

</div>
