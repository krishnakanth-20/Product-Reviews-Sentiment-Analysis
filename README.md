# 🛍️ Product Reviews Sentiment Analysis using Transformers

## 📌 Project Overview

**Product Reviews Sentiment Analysis** is a Natural Language Processing (NLP) project that analyzes customer product reviews and classifies them into different sentiment categories such as:

* 😊 **Positive**
* 😐 **Neutral**
* 😞 **Negative**

The project uses **Transformer-based sentence embeddings** to understand the semantic meaning and context of customer reviews. These embeddings are then used with machine learning classification algorithms to predict the sentiment of each review.

The main goal is to automate customer feedback analysis and help businesses understand customer opinions efficiently.

---

## 🎯 Problem Statement

Product reviews contain valuable information about customer satisfaction, product quality, usability, and overall experience.

However, manually analyzing a large number of reviews is time-consuming and difficult.

This project provides an automated solution that:

1. Processes customer reviews.
2. Converts review text into meaningful numerical representations.
3. Uses Transformer-based embeddings to capture the context of the text.
4. Classifies reviews into Positive, Neutral, or Negative sentiment.
5. Evaluates classification performance using accuracy and F1-score.

---

## 🎯 Objectives

* Perform sentiment analysis on product reviews.
* Apply Natural Language Processing techniques.
* Generate sentence embeddings using Transformer models.
* Train machine learning classification models.
* Compare model performance.
* Evaluate models using Accuracy and F1-score.
* Provide useful insights into customer opinions.

---

## 📊 Dataset

The dataset contains **1,007 records and 3 columns**.

### Dataset Columns

| Column           | Description                                 |
| ---------------- | ------------------------------------------- |
| `Product ID`     | Unique identification number of the product |
| `Product Review` | Customer review or feedback                 |
| `Sentiment`      | Sentiment category of the review            |

### Sentiment Distribution

The dataset contains approximately:

* **Positive:** 850 reviews
* **Neutral:** 75 reviews
* **Negative:** 75 reviews

This shows that the dataset is highly dominated by positive reviews.

---

## 🧠 Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Sentence Transformers**
* **Transformers**
* **PyTorch**
* **Google Colab**
* **Matplotlib / Seaborn** *(for visualization where applicable)*

---

## 🤖 Transformer Model

The project uses the pre-trained:

### `all-MiniLM-L6-v2`

from the Sentence Transformers library.

The model converts e
