# Netflix Data Analysis using SQL

## Project Overview

This project analyzes the Netflix dataset using SQL to extract meaningful insights about movies and TV shows available on Netflix.

The analysis focuses on:
- content distribution
- genre analysis
- country-wise trends
- ratings
- release years
- directors and actors
- movie vs TV show comparisons

The goal of this project is to demonstrate SQL querying skills, data analysis, and business insight generation using a real-world dataset.

---

# Dataset Information

Dataset: `netflix_titles.csv`

The dataset contains information about Netflix titles, including:

| Column | Description |
|---|---|
| show_id | Unique ID of the title |
| type | Movie or TV Show |
| title | Name of the title |
| director | Director name |
| cast | Cast members |
| country | Country of origin |
| date_added | Date added to Netflix |
| release_year | Release year |
| rating | Content rating |
| duration | Duration of content |
| listed_in | Genre/category |
| description | Short description |

---

# Technologies Used

- SQL
- MySQL / PostgreSQL / SQL Server
- CSV Dataset

---

# Business Problems

1. Count the number of Movies vs TV Shows available on Netflix.

2. Find the most common rating for Movies and TV Shows.

3. List all movies released in a specific year (example: 2020).

4. Find the top 5 countries with the most content on Netflix.

5. Identify the longest movie available on Netflix.

6. Find content added to Netflix in the last 5 years.

7. Find all Movies/TV Shows directed by 'Rajiv Chilaka'.

8. List all TV Shows with more than 5 seasons.

9. Count the number of content items in each genre.

10. Find each year and the average number of content releases in India on Netflix and identify the top 5 years with the highest average content release.

11. List all movies categorized as Documentaries.

12. Find all content without a director.

13. Find how many movies actor 'Salman Khan' appeared in during the last 10 years.

14. Find the top 10 actors who appeared in the highest number of movies produced in India.

15. Categorize content based on the presence of keywords like 'kill' and 'violence' in the description field and count how many items fall into each category.
---

# SQL Analysis Performed

## Data Exploration
- Total number of records
- Null value checks
- Distinct category analysis

## Content Analysis
- Movie vs TV Show count
- Most common ratings
- Most popular genres
- Longest movies
- Recent releases

## Time-Based Analysis
- Content added by year
- Release trends over time

## Country-Based Analysis
- Top countries producing content
- Country-wise content distribution

## Director & Cast Analysis
- Most frequent directors
- Actor appearance analysis

---

# Key Insights

- Movies are more common than TV Shows on Netflix.
- The United States contributes the highest amount of content.
- Drama and International Movies are among the most popular genres.
- Netflix content additions increased significantly after 2015.
- TV-MA is one of the most frequent content ratings.

---

# Project Structure

```text id="a1k8pj"
├── netflix data analysis.sql
├── netflix_titles.csv
├── README.md
```

---

# How to Run

1. Import the dataset into your SQL database.

2. Run the SQL queries from:

```text id="h0yqim"
netflix data analysis.sql
```

3. Analyze the generated insights.

---

# Skills Demonstrated

- SQL Query Writing
- Data Cleaning
- Aggregations
- GROUP BY Operations
- Filtering and Sorting
- Business Insight Generation
- Exploratory Data Analysis

---

# Author

Abhishek Ujjeli
```
