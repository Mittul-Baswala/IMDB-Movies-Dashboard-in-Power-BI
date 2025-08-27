# 🎬 Interactive IMDb Movie Dashboard with Power BI
<img width="1569" height="893" alt="Image" src="https://github.com/user-attachments/assets/2f13f369-5e0c-48f1-b36f-269b935cc6cb" />
*COMPANY NAME* : CODTECH IT SOLUTIONS 

*NAME*: MITTUL BASWALA

*INTERN ID*: CT06DZ2256

*DOMAIN*: DATA ANALYTICS

*MENTOR*: NEELA SANTOSH

## 🎯 Project Overview

This project presents a dynamic, interactive dashboard developed in Microsoft Power BI to analyze the IMDb Top 1000 Movies dataset. The primary goal is to move beyond static numbers and uncover the hidden trends, patterns, and correlations that define a successful film—both commercially and critically.
This dashboard is designed as a strategic tool for stakeholders like studio executives, producers, or film analysts to explore complex data in an intuitive way. By dynamically filtering and drilling down into the data, users can get answers to crucial business questions, validate hypotheses, and make data-driven decisions.

## 🤔 Key Questions Addressed:

-Performance Analysis: What are the highest-grossing movie genres, and do they also have the best critical reception?
-Success Correlation: Is there a direct and provable correlation between a movie's gross revenue and its IMDb rating?
-Talent Analytics: Which directors consistently deliver successful films, creating a "bankable" track record?
-Evolution of Cinema: How have key metrics like genre popularity and average ratings evolved over the decades?

## ✨ Features & Visuals

This dashboard integrates a suite of interactive features and purpose-driven visuals to provide a comprehensive analysis.
### Executive Summary KPI Cards: 📈 At-a-glance metrics provide an immediate high-level summary of the entire dataset:
-Total Gross Revenue: $937M
-Average IMDb Rating: 7.94
-Total Count of Movies: 999
### Interactive Slicers: 🎛️ Dynamically filter the entire dashboard by:
-Genre: Isolate one or more genres to compare their performance.
-Released Year: Use the slider to analyze specific time periods (e.g., movies from the 1990s).
-Director: Drill down into the filmography of a specific director.
### Top Genre by Revenue (Bar Chart): Instantly identifies which genres, such as Drama and Action, are the most commercially successful.
### Ratings vs. Revenue (Scatter Plot): Visualizes the complex relationship between critical acclaim (IMDb Ratings) and commercial success (Revenue), helping to identify outliers and trends.
### Trends Over Time (Line Chart): Tracks the average IMDb rating of movies from 1920 to 2020, showing the evolution of filmmaking and audience reception.
### Number of Votes for Each Genre (Bar Chart): Complements the revenue analysis by showing which genres attract the most audience engagement in the form of votes.

## 💾 Dataset

-The analysis is based on the IMDb Top 1000 Movies Dataset, a rich and comprehensive collection of film data.
-Source: IMDb Dataset on Kaggle[https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows]
-Why this dataset? It's ideal for this project because it contains a healthy mix of categorical (Genre, Director), numerical (Gross, IMDB_Rating), and time-series (Released_Year) data, making it perfect for a  multi-faceted analysis.

## 🛠️ Tools and Technologies
-Data Analysis and Visualization: Microsoft Power BI
-Why Power BI? It was chosen for its powerful data modeling capabilities, user-friendly interface, and seamless interactive features that allow for rapid development of complex dashboards.
-Data Cleaning and Transformation: Power Query Editor (within Power BI)

## 🧠 Methodology
-The project followed a structured data analysis workflow from raw data to actionable insights:
-Data Loading & Transformation (ETL):
  -Connected to the raw CSV data source using Power BI's Get Data feature.
  -Utilized the Power Query Editor to perform critical cleaning and shaping tasks:
  -Handled Missing Values: Removed or replaced null values in the Gross and Metascore columns to ensure calculation accuracy.
  -Corrected Data Types: Ensured that numerical columns (Released_Year, Gross) and date columns were correctly formatted for proper analysis.
  -Split 'Genre' Column: Transformed the multi-value Genre column (e.g., "Action, Adventure, Sci-Fi") into individual rows for each genre. This crucial step normalizes the data, enabling accurate filtering.
-Data Modeling & DAX:
  -A simple data model was used, with basic DAX (Data Analysis Expressions) measures created for aggregations like Average IMDb Rating and Total Gross Revenue.
-Visualization & Dashboard Design:
  -Designed a clean, intuitive layout with the most important KPIs at the top.
  -Configured interactivity using Slicers and Power BI's default cross-filtering capabilities to empower user-driven exploration.
## 💡 Actionable Insights
The interactive analysis revealed several key takeaways directly from the dashboard:
-Prioritize High-Concept Genres: 💰 "For maximizing box office returns, the studio should prioritize funding high-concept Action/Adventure projects. Dramas should be pursued with smaller budgets for portfolio diversity and awards potential."
-Aim for the "Sweet Spot" Rating: 📈 "We should aim for films that are well-received (7.5+ rating) but focus marketing efforts on genre, cast, and spectacle, as these are stronger drivers of blockbuster revenue than critical acclaim alone."

## 🚀 How to Use
-Download the .pbix file from this repository.
-Open the file using the Power BI Desktop application (it's free to download).
-Use the slicers on the left-hand side to filter the data by your criteria.
-Click on any data point in a chart (e.g., a genre, a director's name) to see all other visuals update in real-time.
-Hover over visuals to see detailed tooltips with specific numbers.
