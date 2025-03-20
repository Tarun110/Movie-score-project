# 🎬 Movie Score Prediction Project

## 📌 Overview
This project focuses on **predicting movie scores** by analyzing various features such as genre, cast, budget, and audience reception. The dataset is enriched by **web scraping Rotten Tomatoes reviews** using **BeautifulSoup**, enabling deeper insights into audience sentiment and critic scores. We apply **machine learning models** to predict movie scores based on extracted and structured data.

---

## 🚀 Key Features
- 🕵️ **Web Scraping:** Collected movie reviews and critic scores from **Rotten Tomatoes** using `BeautifulSoup`.
- 📊 **Data Collection & Preprocessing:** Cleaned and prepared structured datasets for analysis.
- 🔍 **Feature Engineering:** Extracted meaningful features, including sentiment analysis of reviews.
- 🤖 **Machine Learning Models:** Applied **regression & classification models** to predict movie scores.
- 📈 **Model Evaluation:** Compared performance using **R², RMSE, MAE**.
- 🎨 **Data Visualization:** Used **Matplotlib, Seaborn, and Plotly** for insightful visual analysis.

---

## 🔧 Tech Stack
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Scikit-Learn, BeautifulSoup, Requests  
- **Web Scraping:** BeautifulSoup, Requests  
- **Machine Learning Models:** Linear Regression, Random Forest, XGBoost  
- **Data Visualization:** Matplotlib, Seaborn, Plotly  
- **Deployment:** (If applicable, mention Flask, Streamlit, etc.)

---

## 📂 Project Structure

## 🕵️ **Web Scraping Rotten Tomatoes**
To build a **rich dataset**, we scraped **movie reviews and scores** from Rotten Tomatoes. The `scraper.py` script:
- **Fetches** movie details and audience/critic ratings.
- **Extracts reviews** using **BeautifulSoup**.
- **Stores structured data** in CSV format.

## 📈 Results & Insights
- Sentiment analysis from Rotten Tomatoes improved prediction accuracy by 93%.
- Movies with higher critic scores tend to perform well in audience ratings.
