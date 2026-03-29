# 🎬 Amazon Prime TV Shows & Review Analysis

A data science capstone project by **Siddharth Purswani** that explores Amazon Prime Video's TV show catalog and user review data to uncover trends, genre patterns, viewer sentiment, and content performance insights.

---

## 📌 Project Overview

This project performs an end-to-end exploratory and analytical study of Amazon Prime Video's TV show library. It combines structured metadata analysis with natural language processing (NLP) on user reviews to derive actionable insights about content quality, viewer preferences, and platform trends.

---

## 🎯 Objectives

- Analyze the distribution of TV shows across genres, release years, ratings, and regions
- Perform sentiment analysis on user reviews to understand viewer reception
- Identify top-performing shows based on ratings and review volume
- Discover trends in Amazon Prime's content library over time
- Visualize patterns to support data-driven content recommendations

---

## 📁 Project Structure

```
Amazon_Prime_TV_Shows_and_Review_Analysis/
│
├── Amazon_Prime_TV_Shows_and_Review_Analysis_Captone_Project_Siddharth_Purswani.ipynb
│                          # Main Jupyter Notebook with full analysis
├── data/
│   ├── amazon_prime_titles.csv        # TV show metadata (title, genre, rating, etc.)
│   └── reviews.csv                    # User reviews and ratings
├── images/                            # Saved visualizations (if any)
└── README.md
```

---

## 📊 Dataset

| Dataset | Description |
|---|---|
| `amazon_prime_titles.csv` | Contains show metadata: title, type, director, cast, country, release year, rating, duration, genres, description |
| `reviews.csv` | Contains user-submitted reviews: show title, star rating, review text, date |

> **Source:** Datasets sourced from [Kaggle - Amazon Prime Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows)

---

## 🔍 Key Analyses

### 1. 📈 Exploratory Data Analysis (EDA)
- Distribution of TV shows vs. movies
- Top genres and sub-genres on the platform
- Release year trends — how the catalog has grown over time
- Country-wise content distribution
- Content rating breakdown (TV-MA, TV-14, PG-13, etc.)

### 2. 🌍 Content Geography
- Heatmaps and bar charts showing which countries produce the most content
- Analysis of international vs. US-origin content

### 3. ⭐ Ratings & Popularity
- Distribution of show ratings
- Most-reviewed and highest-rated shows
- Correlation between number of reviews and average star rating

### 4. 📅 Trend Analysis
- Year-over-year growth in content additions
- Genre popularity trends across decades

---

## 🛠️ Tech Stack

| Category | Tools / Libraries |
|---|---|
| Language | Python 3.x |
| Data Manipulation | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Plotly
| Environment | Jupyter Notebook |

---

## ⚙️ Setup & Usage

### Prerequisites
Make sure you have Python 3.7+ installed.

### Installation

```bash
# Clone the repository
git clone https://github.com/siddharthpurswani/Amazon_Prime_TV_Shows_and_Review_Analysis.git
cd Amazon_Prime_TV_Shows_and_Review_Analysis

# Install required libraries
pip install pandas numpy matplotlib seaborn plotly nltk textblob wordcloud jupyter
```

### Running the Notebook

```bash
jupyter notebook Amazon_Prime_TV_Shows_and_Review_Analysis_Captone_Project_Siddharth_Purswani.ipynb
```

Run all cells sequentially. Ensure the dataset files are placed in the correct directory before execution.

---

## 📷 Sample Visualizations

> *(Generated during notebook execution)*

- 📊 Genre distribution bar chart
- 🗺️ Country-wise content heatmap
- 📉 Sentiment score distribution
- 📅 Content release timeline

---

## 💡 Key Findings

- **Drama** and **Comedy** are the most prevalent genres on Amazon Prime Video.
- Content additions saw a sharp increase post-2015, reflecting Prime's aggressive expansion.
- A significant portion of user reviews are **positive**, with sentiment scores skewing favorably.
- All the shows are from the **United States**
- High review volume does not always correlate with high average ratings.

---

## 🙋 Author

**Siddharth Purswani**  
📧 [GitHub Profile](https://github.com/siddharthpurswani)

---

## 🤝 Acknowledgements

- Dataset: [Kaggle - Shivam Bansal](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows)
- Inspiration: Amazon Prime Video content strategy research
- Capstone project submitted as part of a Data Science / Data Analytics program
