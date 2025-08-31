# 📊 Netflix Movies and TV Shows EDA

## 🔍 Project Overview
This project is an **Exploratory Data Analysis (EDA)** of the Netflix Movies and TV Shows dataset from Kaggle.  
The goal was to analyze the content available on Netflix and uncover insights about its distribution, growth trends, genres, ratings, and country-wise contributions.

This project is part of my **Data Science learning roadmap** — focused on building strong fundamentals in data cleaning, visualization, and storytelling.

---

## 📂 Dataset
- **Source**: [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
- **File Used**: `netflix_titles.csv`  
- **Size**: ~8800 rows, 12 columns  
- **Columns**:  
  - `type`: Movie / TV Show  
  - `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`  

---

## 🛠️ Skills & Tools
- **Python**: `pandas`, `numpy`  
- **Visualization**: `matplotlib`, `seaborn`  
- **EDA techniques**: Handling missing values, feature engineering (`year_added`, `movie_minutes`, `seasons`), exploding multi-valued columns (`genres`, `countries`, `cast`)  

---

## 📊 Key Insights
1. ~70% of content is **Movies**, while 30% is **TV Shows** — though TV shows are increasing.  
2. Content growth peaked in **2018–2019** and slowed afterward.  
3. Most popular genres: **International Movies**, **Dramas**, **Comedies**.  
4. **United States, India, and the UK** dominate content production.  
5. Ratings are skewed toward **TV-MA** and **TV-14**, targeting teens/adults.  
6. Movies are typically **90–120 minutes long**, while most TV shows have **1–2 seasons**.  
7. Recent years show a **slight decline in movie duration** — Netflix appears to be favoring shorter content.  

---

## 📈 Visualizations
The notebook includes:  
- Movies vs TV Shows distribution  
- Content growth over years  
- Top 10 genres & countries  
- Ratings distribution  
- Movie duration & TV season histograms  
- Trends in genre popularity over time  

---

## 🚀 How to Run
1. Clone this repository  
2. Install requirements:  
   ```bash
   pip install numpy pandas matplotlib seaborn jupyter
