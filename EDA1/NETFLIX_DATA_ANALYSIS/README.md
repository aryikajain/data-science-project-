# data-science-project-
#  Netflix Data Analysis – Exploratory Data Science Project

##  Overview
This project explores the **Netflix Titles Dataset** from Kaggle to understand the content trends, genre distribution, and country-wise production patterns on the platform.  
It focuses on **data cleaning, analysis, and visualization** using Python libraries like **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**.

Through this project, I aimed to answer key questions such as:
- Which country produces the most Netflix content?
- What is the ratio of Movies vs TV Shows?
- How has Netflix’s content grown over the years?
- What are the most popular genres and trends?

---

##  Objectives
- Perform **data cleaning and preprocessing**
- Handle **missing values** and **duplicates**
- Conduct **exploratory data analysis (EDA)** for key insights
- Create **visualizations** to tell a data-driven story
- Understand **content trends by country, type, and release year**

---

##  Dataset
**Source:** [Netflix Movies and TV Shows Dataset – Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
**Description:** The dataset contains information about movies and TV shows available on Netflix, including:
- Title  
- Director  
- Cast  
- Country  
- Release year  
- Rating  
- Duration  
- Listed in (genre/category)  
- Date added  

---

##  Tools & Libraries Used
| Category | Library |
|-----------|----------|
| Data Handling | `pandas`, `numpy` |
| Visualization | `matplotlib`, `seaborn` |

---

##  Data Cleaning Steps
- Removed missing or duplicate entries
- Cleaned the `country`, `date_added`, and `duration` columns
- Converted date columns to datetime format
- Handled categorical data for visualization

---

##  Exploratory Data Analysis (EDA)
Key analyses and visualizations include:
- **Movies vs TV Shows** count
- **Top 10 countries** producing the most content
- **Content release trend over the years**
- **Most popular genres**
- **Frequent directors and cast appearances**
- **Seasonal trend**: which months Netflix adds most titles

---

## Sample Insights
- The **United States and India** lead in Netflix content production.
- **Movies** dominate over TV Shows in the catalog.
- There’s a **significant surge in new content** after 2015.
- **Documentaries and Dramas** are among the most frequent genres.

---

## Future Improvements
To make this project more advanced and portfolio-ready:
1. Add **interactive dashboards** using `Streamlit` or `Plotly`
2. Create a **content recommendation system** based on genre/cast similarity
3. Perform **sentiment analysis** on movie descriptions
4. Use **geo-visualizations** (Plotly Choropleth) for country-based insights

---

## What I Learned
- Real-world **data cleaning and wrangling**
- Exploratory Data Analysis (EDA) best practices
- Data storytelling with clear and meaningful visuals
- Deriving actionable insights from raw data
- Presenting results in a professional notebook format

---
## Key Insights
- ~70% of Netflix’s catalog are Movies.
- USA, India, and UK dominate content production.
- Top genres: Drama, Comedy, and International Movies.
- Major growth in content post-2015.
- Netflix focuses on young adult audiences (TV-MA, TV-14)
