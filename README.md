# 🎬 Amazon Prime Streaming Content Analysis

## 📊 Exploratory Data Analysis of Amazon Prime Movies & TV Shows

This project performs a comprehensive **Exploratory Data Analysis (EDA)** on Amazon Prime’s streaming content library to uncover patterns in content distribution, audience ratings, popularity trends, and creative contributions.

The analysis utilizes two datasets containing detailed information about titles and their cast/crew members. By combining statistical insights with visualizations, the project highlights key factors that influence content performance on the Amazon Prime platform.

---

# 📌 Project Overview

The global streaming industry has experienced rapid growth in recent years, with platforms such as **Amazon Prime Video** offering thousands of movies and television series across multiple genres, languages, and countries.

Analyzing such a massive catalog helps uncover patterns related to:

- Viewer preferences
- Content popularity
- Genre performance
- Global production trends
- Ratings and engagement

This project aims to explore these aspects using **Python-based data analysis and visualization techniques**.

---

# 🎯 Business Objective

The main objective of this project is to analyze Amazon Prime’s content dataset in order to identify insights that support **data-driven decision making in content strategy**.

Through this analysis, we aim to:

- Understand audience engagement patterns
- Identify high-performing genres and titles
- Evaluate popularity metrics and ratings
- Analyze trends across release years
- Explore the impact of actors, directors, and writers on content success

These insights can help streaming platforms better understand viewer preferences and optimize future content production strategies.

---

# 📂 Dataset Information

This project uses two datasets:

### 1️⃣ titles.csv
Contains information about Amazon Prime movies and TV shows.

Key columns include:

- id
- title
- type
- description
- release_year
- runtime
- genres
- production_countries
- age_certification
- imdb_score
- tmdb_score
- tmdb_popularity
- imdb_votes

---

### 2️⃣ credits.csv
Contains details about cast and crew members involved in each title.

Key columns include:

- person_id
- id
- name
- character
- role

---

# 🛠️ Tools & Technologies Used

| Tool | Purpose |
|-----|------|
| Python | Data analysis |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Analysis environment |

---

## 📁 Project Structure

```bash
Amazon-Prime-Streaming-Content-Analysis
│
├── Datasets
│   ├── titles.csv
│   └── credits.csv
│
├── Analysis.ipynb
└── README.md
```

---

# 🔎 Data Processing Steps

The following steps were performed during the analysis:

### Data Loading
- Import datasets using Pandas

### Data Understanding
- Inspect dataset structure
- Check rows and columns
- Review column data types

### Data Cleaning
- Handle missing values
- Remove duplicate records
- Replace missing age certification values
- Fill missing IMDb scores using mean values

### Feature Engineering
New features were created including:

- **Decade column**
- **Runtime category** (Short / Medium / Long)
- **Rating category** (Poor / Average / Good / Excellent)

### Dataset Integration
The **titles** and **credits** datasets were merged using the **id column**.

---

# 📊 Key Performance Indicators (KPIs)

Several important metrics were calculated including:

- Total number of titles
- Number of movies vs TV shows
- Average runtime
- Average IMDb score
- Release year range
- Genre popularity
- Country-wise production distribution
- Top actors, directors, and writers

---

# 📈 Exploratory Data Analysis

The project includes multiple visualizations to uncover trends and relationships.

### Content Distribution
- Movies vs TV Shows comparison

### Runtime Distribution
- Histogram showing distribution of movie runtime

### Release Trends
- Number of titles released per year

### Genre Analysis
- Top genres by count
- Average IMDb rating by genre

### Rating Distribution
- IMDb score distribution

### Genre Heatmap
- Average IMDb rating by genre

### Popular Titles
- Top rated titles
- Most popular titles based on TMDB popularity

### Cast & Crew Analysis
- Top actors
- Top directors
- Role distribution

### Global Production Insights
- Top countries producing Amazon Prime content

### Certification Analysis
- Distribution of age certifications
- Average rating by certification

### Correlation Analysis
- IMDb vs TMDB score relationship
- Popularity vs rating relationship

---

# 📊 Key Insights

From the analysis, several important insights were discovered:

### Content Distribution
Movies dominate the Amazon Prime catalog compared to TV shows.

### Genre Popularity
Drama, comedy, and documentary genres appear frequently within the dataset.

### Rating Trends
Higher rated titles tend to cluster between **6 and 8 IMDb scores**.

### Release Growth
Content production has increased significantly over recent years, reflecting the expansion of streaming platforms.

### Popularity vs Ratings
Some titles with high popularity do not always have the highest ratings, indicating a difference between audience engagement and critical reception.

### Global Production
The United States contributes the largest share of content production.

### Creative Contributors
Certain actors and directors appear repeatedly across multiple titles, indicating strong industry influence.

---

# 📷 Sample Visualizations

The project includes several charts such as:

- Movie vs Show distribution
- IMDb score distribution
- Genre heatmaps
- Top rated titles
- Popular titles ranking
- Actor and director frequency charts
- Country-wise production analysis

These visualizations provide meaningful insights into the Amazon Prime content ecosystem.

---

# 🚀 Future Improvements

Possible extensions for this project include:

- Building recommendation systems
- Applying machine learning models for rating prediction
- Sentiment analysis on content descriptions
- Advanced dashboard creation using **Power BI or Tableau**

---

# 👨‍💻 Author

**Sumit Bhatt**

Data Analyst | Python | SQL | Power BI

---

# 🔗 Project Repository

GitHub Repository:

https://github.com/Sumit-Bhatt-443/Amazon-Prime-Streaming-Content-Analysis

---

# ⭐ Final Thoughts

This exploratory data analysis highlights how data-driven insights can help understand streaming platform content strategies, audience preferences, and global entertainment trends.

By combining **statistical analysis and visualization**, this project demonstrates the potential of data analytics in shaping decisions within the digital entertainment industry.
