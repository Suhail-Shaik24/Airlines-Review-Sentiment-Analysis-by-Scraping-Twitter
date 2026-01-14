## Overview

This project performs sentiment analysis on airline customer reviews collected from Twitter. By scraping airline-related tweets and applying Natural Language Processing (NLP) and Machine Learning / Deep Learning techniques, the system classifies public sentiment into Positive, Negative, or Neutral categories. The goal is to understand customer satisfaction, service quality, and overall public perception of different airlines.

---

## Objectives

* Scrape airline-related tweets from Twitter
* Clean and preprocess raw tweet data
* Perform sentiment classification using ML / DL models
* Analyze and visualize customer opinions
* Provide insights into airline service quality

---

## Technologies Used

* Programming Language: Python
* Web Scraping: Tweepy / SNScrape
* NLP Libraries: NLTK, spaCy
* Machine Learning: Scikit-learn
* Deep Learning (optional): BERT / Transformers
* Visualization: Matplotlib, Seaborn
* Web App (optional): Streamlit

---

## Project Workflow

1. Data Collection

   * Scrape tweets mentioning airlines using keywords and hashtags

1. Data Preprocessing

   * Remove URLs, mentions, hashtags, emojis
   * Tokenization
   * Stopword removal
   * Lemmatization

1. Feature Engineering

   * TF-IDF / Word Embeddings

1. Sentiment Classification

   * Machine Learning models (Naive Bayes, Logistic Regression)
   * Deep Learning models (BERT, LSTM – optional)

1. Evaluation

   * Accuracy, Precision, Recall, F1-score

1. Visualization & Insights

   * Sentiment distribution plots
   * Airline-wise sentiment comparison

---

## Dataset

* Tweets scraped directly from Twitter using airline-specific keywords
* Example keywords: `@IndiGo6E`, `@airindia`, `@united`, `@delta`

>  Note: Twitter data is scraped in compliance with platform policies and used only for educational purposes.

---

##  How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Suhail-Shaik24/Airlines-Review-Sentiment-Analysis-by-Scraping-Twitter.git
cd Airlines-Review-Sentiment-Analysis-by-Scraping-Twitter
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Scrape Tweets

```bash
python scrape_tweets.py
```

### 4️⃣ Train the Model

```bash
python train_model.py
```

### 5️⃣ Run the Application (Optional)

```bash
streamlit run app.py
```

---

## 📈 Results

* Successfully classified airline tweets into sentiment categories
* Observed dominant negative sentiment during delays and cancellations
* Positive sentiment linked to customer service responses

---

## Future Enhancements

* Real-time Twitter sentiment analysis
* Multilingual tweet support
* Aspect-based sentiment analysis
* Dashboard with interactive analytics
* Deployment on cloud platforms

---

## References

* Twitter API / SNScrape Documentation
* Hugging Face Transformers
* NLTK Documentation

---
⭐ If you like this project, give it a star !
