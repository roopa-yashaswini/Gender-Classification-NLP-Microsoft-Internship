# 🧠 Twitter Gender Classification Using NLP Techniques Microsoft-Internship

# 🧠 Twitter Gender Classification Using NLP Techniques

## 📌 Project Overview

This project focuses on using Natural Language Processing (NLP) techniques to classify Twitter users by gender — male, female, or brand — based on their tweet content and user metadata. The objective is to preprocess and analyze user-generated text to uncover linguistic and behavioral patterns that differentiate these groups.

---

## 🗃️ Dataset Summary

- Source: Pre-shared Twitter dataset (CSV)
- Classes: `male`, `female`, `brand`
- Core text field: `text` (user tweet content)
- Additional metadata: `tweet_count`, `retweet_count`, `gender`

After preprocessing, entries labeled as `unknown` gender were excluded to improve classification relevance.

---

## 🧠 NLP Techniques Applied

### 🧹 Text Preprocessing
- **Lowercasing** all text for normalization
- **Removal of digits**, URLs, special characters, and punctuation
- **Token filtering** to exclude mentions (@), hashtags (#), and hyperlinks
- **Regular expressions** for string cleaning
- Cleaned text is stored as a new processed feature ready for NLP modeling

### 🧾 Feature Engineering
- **Hashtag frequency** per gender category
- **Text length analysis**
- **Retweet and tweet volume** correlation by gender

These features enhance model interpretability and may be used in combination with vectorized text in future classifiers.

---

## 📊 Exploratory Data Analysis (EDA)

- Countplot of records per gender category
- Barplot of tweet/retweet counts by gender
- Hashtag usage comparisons across gender labels
- Visualization of tag density to assess user engagement style


---

## 🛠 Tools & Libraries

- **Python**: `pandas`, `matplotlib`, `seaborn`, `re`, `numpy`
- **NLP Preprocessing**: `re` for regex-based text normalization
- **Visualization**: `matplotlib`, `seaborn`

---

## 📦 File Structure

```
.
├── ML07B16_code.ipynb         # Notebook with preprocessing, cleaning, and EDA
├── Information (2).csv        # Input Twitter dataset
└── README.md                  # Project documentation
```

---

## 👤 Author

Roopa Yashaswini Kotha  
London Business School – NLP & Text Classification Project
