# 🎮 Supercell Player Sentiment Intelligence Dashboard

This project analyzes player feedback from Supercell game communities to uncover key frustrations, gameplay concerns, and churn signals. Using NLP + Interactive Dashboards, player sentiment trends are translated into actionable product insights.

---

## 🚀 Project Goals

✔ Analyze community feedback to identify major gameplay pain points regarding the most recent update
✔ Detect negative sentiments tied to key topics , categoried and events  
✔ Provide product teams with insights for improving player retention  

---

### 🧩 Dataset Summary

| Feature     | Description |
|------------|-------------|
| **category** | Discussion type — *Heroes*, *Level-16*, *Play Store Reviews* |
| **rating**   | Player rating scale from ★1 to ★5 |
| **date**     | Timestamp used for time-series sentiment trends |
| **source**   | Review platform — *YouTube* or *Google Play* |
| **sentiment** | NLP-based classification — *negative*, *neutral*, *positive* |
| **topic**    | Complaint theme extracted from LDA topic modeling |

📌 **Record Count:** ~25,000 reviews  
📌 **Time Period:** 2025 Recent Game Update Discussions

---

## 🧠 Methodology

| Stage | Tools | Outcome |
|------|------|---------|
| Data Cleaning | Python, Regex | Filtered noise, edited tags |
| Sentiment Analysis | Hugging Face Pipeline for Sentiment Analysis| Polarity score for each review |
| Text Vectorization | TF-IDF | Machine-readable representation for Predicting Ratings |
| Topic Modeling | RoBERTa sentence embeddings + KMeans  | Top complaint themes |
| Visualization | Power BI | Business insights dashboard |

---

## 🔎 Key Insights Overview

 • **Negative sentiment dominates following the recent update, indicating player dissatisfaction with new changes.**

 • **Gameplay-related topics generate the highest review volume. Players are highly concerned about balancing and mechanics.**

 • **Google Play reviews are fewer compared to YouTube but show a higher positive sentiment share, suggesting differences in feedback behavior across platforms.**

---

## 🛠 Tech Stack

- **Python** (Pandas, NumPy, Scikit-Learn, NLTK , NLP , Transformers , TF-IDF)
- **Power BI** (multi-page dashboard)

---

## 🧩 Solution Preview
<img width="1426" height="734" alt="image" src="https://github.com/user-attachments/assets/f68b327d-1066-405f-8987-76de425f4d27" />
<img width="1418" height="738" alt="image" src="https://github.com/user-attachments/assets/5aebb688-576a-442d-b5b9-1d458bac0674" />
<img width="1378" height="735" alt="image" src="https://github.com/user-attachments/assets/7bff7cd6-534c-4915-9ea0-e95a9bcd605b" />




