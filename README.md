# 🎥 Studio Ghibli Streaming Analytics Dashboard  

**An end-to-end data analytics project using Excel, SQL & Tableau**

### > 🎯 View the interactive Tableau dashboard here:  
[🔗 Tableau Public Link](#) https://public.tableau.com/views/StudioGhibliStreamingAnalytics/Dashboard?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

![Dashboard Screenshot](images/Screenshot 2025-06-24 at 14.08.18.png)

---

## 📊 Project Overview

This project explores user engagement, content performance, and financial metrics for a fictional Studio Ghibli streaming platform. Built using Excel (data cleaning), SQL (advanced queries), and Tableau (interactive dashboard), the project delivers actionable insights to help drive content strategy, marketing, and viewer retention.

---

## 🧰 Tools Used

- **Excel**: Data cleaning, VLOOKUPs
- **SQL**: Advanced queries (joins, subqueries, grouping)
- **Tableau**: Interactive visual dashboard
- **Datasets**: 7 CSV files simulating streaming platform data

---

## 🎯 Business Objectives

- Which films perform best by viewer rating and watch completion?
- Which genres are most popular by age group?
- Which directors have the highest average viewer rating?
- How does viewer behavior vary by subscription type?
- What is the ROI (Return on Investment) per film?
- Are there seasonal trends in viewership?
- Which U.S. States have the highest average viewer rating among high active users?
- Who are the top 3 most active users in each U.S. State by number of films watched?

---

## 🔍 Methodology

### Step 1: Data Cleaning (Excel)
- Removed duplicates
- Standardized date and text fields
- Applied VLOOKUP for temporary merges 
- Used formulas like IFERROR, TEXT, VALUE (e.g. converting “1h57mins” into “117”)
- Calculated “Average Rating” and “ROI percent” for each film

### Step 2: Data Modeling (SQL)
- Structured data into relational schema
- Used JOINs, subqueries, and aggregations
- Analyzed key metrics and patterns

### Step 3: Visualization (Tableau)
- Created a one-page interactive dashboard
- Included filters for genre, age group, subscription
- Built charts for ROI, seasonal viewership, and ranking for views/ratings/directors

---

## 🔍 Key Insights

- **Drama & Family** are most popular among teens and young adults.
- Films by **Hayao Miyazaki** consistently receive top viewer ratings.
- ROI peaks for films with moderate budgets but high engagement.
- **May and Fall months** show spikes in viewer activity.

---

## 📘 Lessons Learned

- Gained hands-on experience managing a **normalized multi-table database** and writing advanced SQL queries using `JOIN`s, subqueries, `CASE` statements, and window functions.
- Practiced building a cohesive **end-to-end data pipeline**, from raw data cleaning to visual storytelling using Tableau.
- Learned to translate broad objectives into **specific, actionable data questions** and insights.

---

## 📂 Dataset Overview

The following datasets were used:

- `films.csv`: Film metadata (title, budget, revenue, etc.)
- `directors.csv` & `film_directors.csv`: Director-film relationships
- `genres.csv` & `film_genres.csv`: Genre associations
- `users.csv`: User demographics (age, state, subscription)
- `viewer_stats.csv`: Watch history, ratings, watch durations

---

## 📄 Supporting Materials

- ✅ `films.csv`, `users.csv`, `viewer_stats.csv`, `genre.csv`, `film_genre.csv`, `director.csv`, `film_director.csv`: Original CSV datasets simulating a streaming platform
- ✅ `ghibli_cleaned.xlsx`: Final Excel workbook containing all 7 cleaned datasets in separate sheets
- ✅ `ghibli_sql_analysis.ipynb`: SQL script containing all advanced SQL queries used for analysis (joins, subqueries, aggregations)
- ✅ `ghibli_dashboard.twbx`: Tableau Public dashboard file visualizing viewer behavior, ROI, and trends
- ✅ `README.md`: Full project documentation including objectives, tools, methodology, and key insights

---

## 👋 About the Author

I'm a data analyst passionate about storytelling through data.  
Connect with me on [LinkedIn](#) or check out more projects on [GitHub](#).
