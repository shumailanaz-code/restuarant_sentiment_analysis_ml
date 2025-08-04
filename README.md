# 🍽️ Restaurant Review Sentiment Analysis using VADER

## 📖 Project Overview

A social media management company wants to assess the **overall performance of multiple restaurants** based on customer reviews posted online. 
The goal is to identify which restaurants receive the most negative reviews and provide a **detailed analysis** for the one with the highest negative sentiment.

To achieve this, we used **VADER (Valence Aware Dictionary for Sentiment Reasoning)** — a pre-trained sentiment analysis tool designed for analyzing social media texts.

---

## 🧪 Experimental Procedure

1. Applied **VADER SentimentIntensityAnalyzer** on each review.
2. Extracted the **polarity score** (positive, neutral, negative, compound) for each review.
3. Categorized reviews as **positive** or **negative** based on compound score thresholds.
4. Calculated:
   - Total number of negative and positive reviews
   - Percentage of negative reviews per restaurant
5. Identified the restaurant with the **highest percentage of negative reviews**
6. Performed detailed analysis on that restaurant:
   - Most frequent words in negative and positive reviews
   - Total review volume and rating patterns
   - Time-based trends and visuals (if applicable)

---

## 📊 Dataset Description

| Feature           | Data Type   | Description                                |
|------------------|-------------|--------------------------------------------|
| `Restaurant`      | Categorical | Restaurant name                |
| `Reviewer`        | Categorical |Name of reviewer              |
| `Review`          | Categorical | Text content of the review                 |
| `Rating`          | Numerical   | Given rating (e.g., 1–5 scale)             |
| `Total_Reviews`   | Numerical   | Number of reviews by the reviewer          |
| `Total_Followers` | Numerical   | Reviewer's follower count                  |
| `Time`            | Numerical   | Time of review (e.g., timestamp or hour)   |
| `Pictures`        | Numerical   | Number of pictures shared in the review    |

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**, **NumPy** — Data cleaning & manipulation
- **NLTK** — VADER sentiment analysis
- **Matplotlib**, **Seaborn**, **WordCloud** — Data visualization
- **Jupyter Notebook** — Experimentation & reporting

---

## 📈 Key Insights

- Identified sentiment distribution across all restaurants.
- Found the restaurant with the **highest negative review rate**.
- Analyzed word frequencies to determine **common complaint themes**.
- Visualized top keywords using **word clouds** for both negative and positive sentiments.

---

## 🚀 How to Run

Clone this repository or download the files.
2. Ensure the dataset file `Restuarant_Data.csv` is placed in the root directory or update the file path in the code.
3. Install the required Python packages:
   ```bash
   pip install pandas nltk matplotlib seaborn wordcloud
4. Open the Jupyter Notebook file (sentiment_analysis_ml.ipynb) using Jupyter.
5. Run the notebook cells sequentially to perform sentiment analysis and view visualizations.

---


## 📂 Data Source

The dataset used in this project is sourced from Kaggle.
File Name: Restuarant_Data.csv
