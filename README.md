# 📊 Sentiment Analysis using NLP Pipeline & Machine Learning

## 📌 Project Overview

This project builds a complete end-to-end Sentiment Analysis system
using Natural Language Processing (NLP) and Machine Learning techniques.
The model classifies text data into positive or negative sentiments.

------------------------------------------------------------------------

## 🎯 Objective

To understand how raw text is processed and transformed into meaningful
features, and how different Machine Learning models perform on sentiment
classification.

------------------------------------------------------------------------

## 📂 Dataset

-   Source: Kaggle (IMDb Movie Reviews Dataset)
-   Total Samples: 50,000
-   Features:
    -   review → Text data
    -   sentiment → Label (positive/negative)

------------------------------------------------------------------------

## 🔄 NLP Pipeline

### 1. Data Understanding

-   Loaded dataset using Pandas
-   Explored dataset structure and class distribution

### 2. Text Preprocessing

-   Converted text to lowercase
-   Removed punctuation and special characters
-   Removed stopwords
-   Tokenized text
-   Applied Lemmatization using NLTK

### 3. Feature Engineering

-   Bag of Words (BoW)
-   TF-IDF Vectorization (used for final models)

------------------------------------------------------------------------

## 🤖 Machine Learning Models

-   Logistic Regression
-   Naive Bayes
-   Decision Tree

------------------------------------------------------------------------

## 📊 Model Performance

  Model                 Accuracy
  --------------------- ----------
  Logistic Regression   89.36%
  Naive Bayes           86.66%
  Decision Tree         71.90%

------------------------------------------------------------------------

## 🧠 Insights

-   Logistic Regression performed the best among all models.
-   TF-IDF provided better results compared to Bag of Words.
-   Decision Tree showed lower accuracy due to overfitting.
-   Text preprocessing significantly improved model performance.

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   Python
-   Pandas, NumPy
-   NLTK
-   Scikit-learn
-   Matplotlib / Seaborn

------------------------------------------------------------------------

## 📌 Conclusion

Logistic Regression with TF-IDF is the most effective approach for this
sentiment analysis task.

------------------------------------------------------------------------

## 🚀 How to Run

1.  Clone the repository
2.  Open the notebook (.ipynb)
3.  Run all cells

------------------------------------------------------------------------

## 👩‍💻 Author

Deeksha
