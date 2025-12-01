# 🎬 Movies Analytics: Revenue, ROI, Genres & Director Performance  
### **Exploratory Data Analysis (EDA) on TMDB-Style Movies Dataset (24 Columns)**

This project performs a complete exploratory data analysis (EDA) on a movie metadata dataset that contains **24 features** such as budget, revenue, genres, cast, crew, director, ratings, popularity, and more.  
The goal is to uncover meaningful insights about movie trends, earnings, and performance metrics.

---

## 📁 Dataset Information

**Source:** Kaggle  
**Dataset Name:** TMDB Style Movie Metadata  
**Total Columns:** **24**  

### 📌 Important Columns Used in This Project
- `budget`  
- `revenue`  
- `genres`  
- `keywords`  
- `popularity`  
- `release_date`  
- `runtime`  
- `vote_average`  
- `vote_count`  
- `cast`  
- `crew`  
- `director`  
- `production_companies`  
- `production_countries`  
- `original_language`  
- `title`

Out of the 24 columns, the project majorly uses the most important analytical fields like **budget**, **revenue**, **genres**, **director**, **popularity**, and **ratings**.

---

## 🧹 Data Cleaning Performed
- Converted `release_date` into Datetime format  
- Handled missing values across all numeric columns  
- Cleaned textual columns such as **genres**, **keywords**, **cast**, and **crew**  
- Extracted:
  - `release_year` from `release_date`  
  - `genre_list` from JSON structured genres  
- Created new analytical columns:
  - **profit = revenue - budget**  
  - **ROI (%) = (profit / budget) × 100**  

---

## 📊 Exploratory Data Analysis (EDA)

### ✔ Genre Popularity  
Bar chart showing which genres appear most frequently.

### ✔ Movie Releases Per Year  
Trend line showing yearly movie production patterns.

### ✔ Budget vs Revenue  
Scatter plot showing correlation between budget and earnings.

### ✔ Profit & ROI Analysis  
Identifying movies and genres that give the highest returns.

### ✔ Top Directors by Average Revenue  
Ranking directors based on their mean box-office performance.

---

## 🛠 Tools & Technologies
- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 📁 Project Structure

```
movies-eda-bhaskar/
│── movies_eda_bhaskar.ipynb
│── movie_metadata.csv
│── README.md
└── Project_info.json
```

---

## 🧠 Key Insights (Highlights)
- Action, Drama, and Adventure are the most popular genres.
- Bigger budgets **generally** produce higher revenues, but not always.
- Some low-budget movies deliver extremely high ROI.
- Highest revenue directors consistently create crowd-puller movies.
- Popularity and vote_count strongly influence box-office performance.

---

## 🚀 Conclusion
This EDA successfully reveals deep insights into how different factors such as **genres**, **budget**, **director**, **language**, and **release year** affect a movie’s performance.  
The findings can be extended into prediction models (revenue prediction, rating prediction, or genre classification).

---

## 👨‍💻 Author
**Bhaskar Kotyada**  
Movies EDA — TMDB Dataset (24 Column Analysis)


