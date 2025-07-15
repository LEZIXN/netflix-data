# 🎬 Netflix Movies and TV Shows EDA

This project performs **Exploratory Data Analysis (EDA)** on the **Netflix Movies and TV Shows dataset**. The goal is to understand the trends, patterns, and insights from the data using Python, Pandas, Matplotlib, and Seaborn.

---

## 📌 Dataset Source

- **Name:** Netflix Movies and TV Shows  
- **Source:** [Kaggle - Netflix Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
- **Format:** CSV  
- **Size:** ~6,000+ entries  
- **Last Updated:** 2021

---

## 📝 Features / Columns in the Dataset

| Column Name   | Description                                |
|---------------|--------------------------------------------|
| `show_id`     | Unique ID for each title                   |
| `type`        | Type of content (Movie or TV Show)         |
| `title`       | Name of the content                        |
| `director`    | Director(s) of the content                 |
| `cast`        | Main cast                                  |
| `country`     | Country of production                      |
| `date_added`  | Date added to Netflix                      |
| `release_year`| Year of original release                   |
| `rating`      | Content rating (e.g., PG, TV-MA, etc.)     |
| `duration`    | Duration (in minutes or number of seasons) |
| `listed_in`   | Genre/category                             |
| `description` | Summary of the content                     |

---

## 🔍 Objective

- Clean the dataset (handle missing values, transform data)
- Analyze trends in Netflix content
- Visualize insights using Seaborn and Matplotlib

---

## 📊 Key Analyses

- Distribution of Movies vs TV Shows
- Top genres on Netflix
- Number of titles added per year
- Most popular countries producing content
- Ratings distribution
- Duration trends for movies and TV shows

---

## 🛠️ Tools & Libraries Used

- Python 🐍
- Pandas 📊
- Seaborn 🎨
- Matplotlib 📈
- Jupyter Notebook 🧠

---

## 📈 Sample Visualizations

- Countplot of content type
- Barplot of top 10 genres
- Line plot of content added over years
- Heatmap of correlation (if numeric features are available)

---

## 🚀 How to Run

1. Clone this repository or download the notebook.
2. Install dependencies using pip:
   ```bash
   pip install pandas matplotlib seaborn
