# 🌍 Climate Change Modeling 

This project analyzes public sentiment on climate change using user comments from NASA's official climate change Facebook page. By applying Natural Language Processing (NLP), we extract insights into how people perceive and react to climate-related content over time.

---

## 📌 Project Overview

- **Dataset Source:** NASA Climate Change Facebook Page  
- **Data Size:** 500+ user comments (2020–2023)
- **Tech Stack:** Python, Pandas, Matplotlib, Seaborn, TextBlob
- **Goals:**
  - Perform sentiment analysis
  - Analyze temporal trends in public opinion
  - Explore engagement metrics (likes & replies)
  - Extract dominant discussion topics

---

## 📦 Dataset Description

The dataset includes public comments from NASA’s Facebook page collected between 2020 and 2023. Each row represents a user comment with associated metadata.

**Columns:**
- `Date`: Date and time of the comment
- `Text`: User comment text
- `LikesCount`: Number of likes received
- `CommentsCount`: Number of replies to the comment
- `ProfileName`: Anonymized user name

---

## 🧹 Data Preprocessing

- Removed missing values and duplicates
- Text preprocessing:
  - Lowercasing
  - Removing punctuation, URLs, and stopwords
  - Tokenization and Lemmatization
- Converted `Date` to extract `Year` for trend analysis

---

## 🔍 Exploratory Data Analysis (EDA)

- Analyzed frequency of comments across years
- Checked distribution of likes and replies
- Measured comment lengths and their relation to engagement

---

## ❤️ Sentiment Analysis

- Tool Used: **TextBlob**
- Each comment was assigned a polarity score:
  - **Positive**: Polarity > 0
  - **Neutral**: Polarity = 0
  - **Negative**: Polarity < 0
- Visualized sentiment distribution using bar and pie charts

---

## 📈 Trend Analysis

- Tracked sentiment polarity over time (2020–2023)
- Line plot showed changes in public opinion year-over-year
- Observed peaks during global climate events

---

## 💬 Engagement Insights

- Correlated sentiment with number of likes
- Analyzed comment length vs number of replies
- Found that positive, longer comments gained more interaction

---

## 🧠 Topic Modeling *(Optional / If Done)*

- Applied **LDA** (Latent Dirichlet Allocation) to extract topics
- Identified major themes:
  - Climate activism and awareness
  - Praise or trust in NASA
  - Skepticism or denial

---

## 🔑 Key Takeaways

- Public sentiment was predominantly **positive or concerned**
- Social media reflects real-time public perception of climate issues
- User engagement is influenced by tone and content depth

---

## 🔭 Future Work

- Expand dataset using APIs (Twitter, Reddit, etc.)
- Use advanced NLP models like **BERT**, **RoBERTa**
- Deploy a **real-time sentiment dashboard**
- Perform multi-lingual sentiment analysis

