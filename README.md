# 📊 Amazon Prime Movies & TV Shows Analysis Dashboard

## 📌 Project Overview

This project focuses on analyzing Amazon Prime Movies and TV Shows data using Power BI. The goal of this dashboard is to transform raw entertainment data into meaningful insights that help understand content distribution, genre popularity, ratings, contributors, and content growth trends over the years.

The dashboard provides an interactive and visually appealing way to explore Amazon Prime content through various KPIs, charts, maps, and filters.

---

## 🎯 Problem Statement

Streaming platforms such as Amazon Prime host thousands of movies and TV shows. However, understanding content trends, audience ratings, genre distribution, contributor involvement, and geographical content availability can be challenging without proper visualization.

This project aims to solve the following problems:

* Analyze the distribution of Movies and TV Shows available on Amazon Prime.
* Identify the most popular genres on the platform.
* Understand content release trends over the years.
* Discover the most featured actors and directors.
* Analyze content distribution across different countries.
* Identify top-rated content based on IMDb ratings.
* Provide an interactive dashboard for filtering and exploring content.

---

## 📂 Dataset Information

The project uses two datasets:

### 1. Titles Dataset

Contains information related to:

* Title Name
* Content Type (Movie/Show)
* Genres
* Description
* IMDb Score
* IMDb Votes
* TMDB Score
* TMDB Popularity
* Release Year
* Runtime
* Seasons
* Production Countries
* Age Certification

### 2. Credits Dataset

Contains information related to:

* Actor Names
* Director Names
* Character Names
* Person ID
* Role Information

Both datasets were connected using a common `id` column.

---

## 🧹 Data Cleaning & Transformation

The data was cleaned and transformed using Power Query before visualization.

### Data Cleaning Steps:

* Handled missing values in important columns.
* Replaced null values in Description with "No Description".
* Replaced missing Age Certificates with "Not Rated".
* Verified and corrected data types.
* Removed unnecessary columns where required.
* Cleaned and standardized text values.

### Data Transformation:

* Split multi-value Genre fields into separate rows.
* Cleaned Production Countries data.
* Created relationships between Titles and Credits tables.
* Prepared data for analysis and visualization.

---

## 📈 Key Performance Indicators (KPIs)

The dashboard includes the following KPI cards:

* Total Titles
* Total Movies
* Total TV Shows
* Average IMDb Score
* Average TMDB Score
* Total Actors
* Total Directors

---

## 📊 Dashboard Visualizations

### 🎭 Top Genres

Displays the most popular genres available on Amazon Prime.

### 🎬 Movies vs TV Shows

Shows the distribution of Movies and TV Shows using a donut chart.

### ⭐ Top IMDb Rated Movies & Shows

Highlights the highest-rated content based on IMDb scores.

### 🎥 Top Actors

Displays actors with the highest number of appearances.

### 🎬 Top Directors

Displays directors with the highest number of titles.

### 🌍 Country-wise Content Distribution

Interactive map showing content distribution across countries.

### 📈 Content Release Trend Over Years

Analyzes how content production has changed over time.

### 🎛 Interactive Filters

Users can filter the dashboard by:

* Content Type
* Release Year

---

## 💡 Key Insights

* Movies represent the majority of content available on Amazon Prime.
* Drama and Comedy are among the most dominant genres.
* Content production has significantly increased after the 2000s.
* Certain actors and directors appear frequently across multiple titles.
* Content is distributed across various countries worldwide.
* Top-rated content can be identified using IMDb ratings.

---

## 🛠 Tools & Technologies Used

* Power BI
* Power Query
* DAX (Data Analysis Expressions)
* Data Modeling
* Data Visualization

---

## 📚 Skills Demonstrated

* Data Cleaning
* Data Transformation
* Data Modeling
* Relationship Building
* DAX Measures
* Dashboard Design
* Data Storytelling
* Business Insight Generation

---

## 🚀 Project Outcome

This dashboard successfully transforms raw Amazon Prime content data into actionable insights through interactive visualizations and KPI metrics. It enables users to explore content trends, ratings, genres, contributors, and geographical distribution in a simple and intuitive manner.

---

### 👩‍💻 Developed By
**Jyoti Yadav**
**Tools Used:** Power BI | Power Query | DAX | Data Visualization | Data Analytics
