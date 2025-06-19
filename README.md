# 📧 SpamDetectorApp – Detecting Spam Emails Using Random Forest

This project implements a **spam detection system** using a **Random Forest Classifier**. It processes text data from emails or SMS messages to classify them as either **Spam** or **Not Spam**.

## 🔍 Overview

Spam messages can be harmful or annoying, and automatic detection plays a crucial role in filtering them. This app uses classical machine learning techniques—specifically a Random Forest classifier—to identify and block unwanted spam.

## 📦 Dataset

The dataset used in this project is publicly available on Kaggle:

🔗 [Kaggle: SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

It contains labeled messages as "spam" or "ham" (not spam) and is commonly used for natural language classification tasks.

## 🧠 Model Used

- **Model**: Random Forest Classifier
- **Library**: `scikit-learn`
- **Vectorization**: `TfidfVectorizer` for converting text data to numeric form
- **Preprocessing**:
  - Lowercasing
  - Removal of stopwords, punctuation
  - Tokenization

## ⚙️ Tech Stack

- Python 3.x
- scikit-learn
- pandas
- numpy
- matplotlib / seaborn (for visualization)
- Streamlit (optional, for web interface)

## 🔢 Evaluation Metrics

Below are the evaluation metrics from the classification report on the test set:

