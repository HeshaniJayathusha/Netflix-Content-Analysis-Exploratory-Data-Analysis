# 🎬 Netflix Movies & TV Shows - Exploratory Data Analysis (EDA)

An end-to-end Python exploratory data analysis project examining Netflix titles, release patterns, content ratings, regional contributions, and genre distribution using Pandas, Matplotlib, Seaborn, and WordCloud.

---

## 📌 Project Overview
The objective of this project is to clean, analyze, and visualize the Netflix titles dataset to uncover actionable insights regarding content growth, regional entertainment trends, and target audience demographics.

---

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Data Wrangling:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn, WordCloud
* **Environment:** Google Colab / Jupyter Notebook

---

## 📂 Repository Structure
```text
├── data/
│   └── netflix_titles.csv
├── notebooks/
│   └── Netflix_EDA.ipynb
├── README.md


## 🧼 Data Cleaning & Preprocessing
* **Missing Value Imputation:** Filled null values in categorical fields (`director`, `cast`, `country`, `rating`, `duration`) with `'Unknown'`.
* **DateTime Transformation:** Converted `date_added` into standard `datetime` format to extract chronological patterns (such as `month_added`).
* **Handling Corrupted Records:** Filtered missing `date_added` rows using `dropna(subset=['date_added'])` to ensure clean temporal analysis.

---

## 📊 Key Findings & Business Insights
* **Movies vs TV Shows:** Movies dominate the Netflix library, comprising over 69% of the overall catalog compared to TV Shows.
* **Rapid Expansion Post-2015:** Content additions increased exponentially after 2015, reflecting Netflix's global streaming push.
* **Top Producing Countries:** The United States leads content production, followed by India (heavily dominated by Bollywood movies) and the United Kingdom.
* **Top Genres:** Dramas, International Movies, Comedies, and Documentaries hold the highest share among categories.
* **Content Ratings:** `TV-MA` (Mature Audiences) is the most dominant rating category (~36.5%), followed by `TV-14` (~24.5%), indicating an adult-oriented content acquisition strategy.
*









