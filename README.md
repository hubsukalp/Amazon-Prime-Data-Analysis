# 🎬 Amazon Prime Video Analysis - Capstone Project

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458?style=flat&logo=pandas)
![Seaborn](https://img.shields.io/badge/Library-Seaborn-green?style=flat)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview
This project is an **Exploratory Data Analysis (EDA)** of the Amazon Prime Video dataset, aiming to understand the content strategy of one of the world's largest streaming platforms.

By analyzing over **9,000 titles** and **77,000 cast/crew members**, this project uncovers critical trends in content distribution, audience targeting, and quality consistency. The insights derived act as a strategic guide for improving subscriber retention and growth.

## 📂 Dataset Info
The analysis is based on two primary datasets:
1.  **`titles.csv`**: Contains details of movies and TV shows (ID, Title, Type, Release Year, Age Certification, Runtime, Genres, Production Countries, IMDb Scores, etc.).
2.  **`credits.csv`**: Contains details of the cast and directors associated with every title.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:**
    * **Pandas & NumPy:** For data manipulation and cleaning.
    * **Matplotlib & Seaborn:** For static and interactive visualizations.
    * **Ast:** For parsing stringified list columns (Data Wrangling).

## 📊 Workflow
1.  **Data Wrangling:**
    * Handled missing values in critical columns (`director`, `country`, `age_certification`).
    * Un-nested complex list columns (`genres`, `production_countries`) for granular analysis.
2.  **Exploratory Data Analysis (EDA):**
    * **Univariate Analysis:** Analyzed individual variables (Content Type, Age Ratings).
    * **Bivariate Analysis:** Compared relationships (Movies vs. TV Shows, Score vs. Year).
    * **Multivariate Analysis:** Used Heatmaps and Pairplots to find correlations between Runtime, Popularity, and Ratings.
3.  **Visualization:** Created 15 distinct charts to represent the findings visually.

## 💡 Key Findings & Insights
* **The "Quality vs. Quantity" Dilemma:** The platform is heavily skewed towards Movies (**96%**), but TV Shows (**4%**) consistently outperform Movies in terms of IMDb ratings.
* **Target Audience:** The library is dominated by **Mature (R/TV-MA)** content. There is a significant lack of Family/Kids programming compared to competitors.
* **Runtime Sweet Spot:** The most successful movies adhere strictly to the **90-100 minute** runtime window.
* **Content Boom:** There was a massive exponential spike in content addition between **2015-2020** (The Streaming Wars).

## 🚀 Business Recommendations
Based on the data, the following strategies are recommended:
1.  **Pivot to Series:** Shift acquisition budget from bulk low-rated movies to high-quality **TV Series** to improve retention.
2.  **Family Expansion:** Aggressively acquire **Animated/Family content** to compete with Disney+ and capture the household demographic.
3.  **Runtime Optimization:** Enforce strict production guidelines for original movies to target the **90-100 minute** duration for maximum completion rates.

## ⚙️ How to Run This Project
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR-USERNAME/Amazon-Prime-Data-Analysis.git](https://github.com/YOUR-USERNAME/Amazon-Prime-Data-Analysis.git)
    ```
2.  **Install necessary libraries:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run the Notebook:**
    Open `Amazon_Prime_EDA_Project.ipynb` in Jupyter Notebook or Google Colab.

---
*Created by Sukalp Warhekar as a Data Science Capstone Project.*
