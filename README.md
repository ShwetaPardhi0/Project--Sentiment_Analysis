# 🧠 Sentiment Analysis on Product Reviews

This project applies Natural Language Processing (NLP) techniques to classify customer reviews from Amazon and a product's official site into **Positive**, **Negative**, or **Neutral** sentiments. It uses both traditional NLP methods and transformer-based deep learning models for comparison.

---

## 📌 Project Goals

- Clean and preprocess customer reviews using NLP techniques.
- Analyze and classify review sentiments using:
  - VADER (Lexicon-Based)
  - TextBlob
  - RoBERTa (Transformer-Based)
  - BERT
- Evaluate model performance using source ratings for validation.

---

## 🧰 Technologies Used

- **Languages:** Python
- **Libraries:**
  - NLP: `nltk`, `textblob`, `vaderSentiment`, `transformers`
  - ML: `scikit-learn`
  - Data Handling: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`

---

## 🧠 Models Overview

| Model      | Type              | Highlights                                |
|------------|-------------------|-------------------------------------------|
| VADER      | Lexicon-based     | Best for social media-like text           |
| TextBlob   | Rule-based        | Quick and lightweight sentiment analyzer  |
| BERT       | Transformer-based | Pre-trained language model from Google    |
| RoBERTa    | Transformer-based | Improved variant of BERT by Facebook      |

---

## 🧪 Preprocessing Steps

- Lowercasing and text cleaning
- Tokenization and lemmatization
- Stopwords removal
- Vectorization (TF-IDF and transformer tokenization)

---

## 📊 Evaluation

Sentiment predictions were cross-validated using actual star ratings to measure accuracy.  
📌 **RoBERTa achieved the highest performance** among all models.

---

## 🗂️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sentiment-analysis-nlp.git
   cd sentiment-analysis-nlp
