# 📰 Fake News Detection — Exploratory Text Analysis in Python

This project focuses on the **detection and exploration of fake vs. real news articles** using Python. The analysis combines **data cleaning**, **text preprocessing**, and **visual insights** to understand patterns in deceptive content and how it differs from genuine news.

---

## 🎯 Project Objective

To perform exploratory data analysis (EDA) and text processing on a fake news dataset to:

- Distinguish patterns between **fake** and **real** news
- Explore **word usage**, **subject matter**, and **text length**
- Clean and prepare the dataset for machine learning (future scope)

---

## 📁 Dataset

- **Source**: [Kaggle - Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
- **Files**: `Fake.csv`, `True.csv`
- **Total Articles**: ~44,000  
- **Columns**: `title`, `text`, `subject`, `date`, `label`

---

## 🔧 Data Preprocessing

✔ Merged real and fake news files  
✔ Removed duplicates and missing entries  
✔ Cleaned text using:
  - Lowercasing  
  - Stopword removal  
  - Punctuation cleanup  
  - Lemmatization  

---

## 📊 Exploratory Data Analysis (EDA)

| Visualization           | Insight Provided                         |
|-------------------------|-------------------------------------------|
| 📈 Text Length Distribution | Fake news tends to be longer, on average |
| ☁ Word Clouds             | Distinct word patterns in real vs. fake  |
| 🧠 Subject Distribution    | Real news more politics-focused          |
| 📆 Date Trends            | Spikes in fake news on key political dates|

