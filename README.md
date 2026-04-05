# 🎬 Movie Ratings EDA — MovieLens Dataset

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-EDA-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Overview
Exploratory Data Analysis on the MovieLens dataset (~100,000 ratings) to uncover patterns in user behavior, movie popularity, and genre preferences.

---

## 📂 Dataset
- **Source:** [MovieLens](https://grouplens.org/datasets/movielens/)
- **Size:** ~100,000 ratings
- **Files Used:** `ratings.csv`, `movies.csv`

---

## 🛠️ Tools & Libraries
| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Visualizations |
| Seaborn | Statistical plots |

---

## 📊 Visualizations
- Rating distribution histogram
- Top 20 most rated movies
- Average rating by genre
- Popularity vs rating scatter plot
- User activity trends over time

---

## 🔍 Key Insights
- Average rating is **~3.54**, with a median of **4.0** — users tend to rate positively
- **War and Documentary** genres score highest on average
- Movies with more ratings tend to have **more stable** average scores
- Classic movies (pre-2000) **dominate** high rating counts
- User activity has **increased over time**

---

## 📁 Project Structure
```
Movie-Ratings-EDA-MovieLens/
│
├── data/
│   ├── ratings.csv
│   └── movies.csv
│
├── Movie_Ratings_EDA.ipynb   ← Main notebook
└── README.md
```

---

## ▶️ How to Run
```bash
git clone https://github.com/aryzus/Movie-Ratings-EDA-MovieLens
cd Movie-Ratings-EDA-MovieLens
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook Movie_Ratings_EDA.ipynb
```

---

## 🎯 Outcome
This project demonstrates how EDA can extract meaningful business insights from user-generated data — laying the groundwork for recommendation system development.
