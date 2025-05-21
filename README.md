# Text Review Sentiment Classifier

This repository contains a basic machine learning project that classifies customer reviews as **positive** or **negative**. It demonstrates fundamental concepts in text classification, including preprocessing, feature extraction using TF-IDF, and training simple ML models.

## 📌 Project Overview
**Goal:** Build a machine learning model to classify customer reviews as positive or negative.

**Dataset:** [IMDb Movie Reviews Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)  
(*or replace the link if you used a different dataset*)

## 🧠 Skills Demonstrated
- Text preprocessing (cleaning, tokenization, etc.)
- Feature extraction using TF-IDF
- Model training using Logistic Regression / Naive Bayes / SVM
- Hyperparameter tuning
- Evaluation using accuracy, precision, recall

---

## 📁 Project Structure
├── data/ # Raw or cleaned data
├── notebooks/ # Jupyter notebooks (EDA, model training, etc.)
├── src/ # Python scripts (optional modular code)
├── README.md
└── requirements.txt # Required packages


---

## 🧹 Step 1: Data Preprocessing

- Removed special characters, numbers, and stopwords
- Converted all text to lowercase
- Tokenized text into words

---

## 📊 Step 2: Feature Extraction

Used **TF-IDF** (Term Frequency-Inverse Document Frequency) to convert text into numerical features.

> ✅ **Why TF-IDF?**  
TF-IDF gives importance to words that are frequent in a document but not across all documents, reducing the weight of common words and improving classification performance over Bag of Words.

---

## 🤖 Step 3: Model Selection & Training

Trained models using one of the following:
- Logistic Regression
- Naive Bayes
- Support Vector Machine

Split dataset: **80% training / 20% testing**  
Used **GridSearchCV** to tune hyperparameters.

---

## 📈 Step 4: Evaluation

Evaluated model using:
- Accuracy
- Precision
- Recall
- Confusion Matrix (optional)

---

## 💡 Improvements / Future Scope

- Try deep learning models (e.g., LSTM, BERT)
- Add more labeled data
- Use word embeddings like Word2Vec or GloVe
- Balance dataset (if imbalanced)

---

## 🛠 Requirements

Install the required packages using:
```bash
pip install -r requirements.txt


