# 📊 Sentiment Analysis on Amazon Reviews using NLP and Transformers

## 📝 Overview
This project performs **sentiment analysis** on **Amazon product reviews** using both **traditional NLP methods** and **deep learning-based transformers**. We compare the **VADER (lexicon-based model)** and **RoBERTa (transformer-based model)** to evaluate their effectiveness in classifying sentiments.

## 🚀 Features
- **Exploratory Data Analysis (EDA)**: Visualizes the distribution of review scores.
- **Lexicon-Based Sentiment Analysis (VADER)**: Provides quick sentiment scores.
- **Deep Learning-Based Sentiment Analysis (RoBERTa)**: Uses Hugging Face's pre-trained models for contextual understanding.
- **Named Entity Recognition (NER)**: Extracts entities from reviews.
- **Comparison Between VADER and RoBERTa**: Evaluates differences in sentiment classification.

## 📂 Dataset
- **Source**: Amazon product reviews dataset.
- **Size**: 500 sample reviews.
- **Columns**: Review text, star ratings, user ID, sentiment scores, etc.

## 🧠 Sentiment Analysis Methods
1️⃣ VADER (Valence Aware Dictionary and sEntiment Reasoner)
- A rule-based approach to sentiment analysis, providing negative, neutral, positive, and compound scores.

2️⃣ RoBERTa Transformer Model (Hugging Face)
- A deep learning-based approach that understands context better than VADER.

3️⃣ Hugging Face Sentiment Pipeline (Quick Sentiment Analysis)
- Use a pre-trained model for fast sentiment classification.

## 📈 Results & Comparison
VADER assigns more neutral scores and does not understand sarcasm well.
RoBERTa captures contextual sentiment better but is computationally expensive.

