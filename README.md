# Project-Phase-2
Movie Data Analysis Project
This project presents a comprehensive exploratory data analysis (EDA) of movie industry data, combining box office revenue information with detailed metadata from a SQLite database.

Objectives
Investigate how different movie attributes (genre, runtime, release year, etc.) influence box office performance.

Analyze the correlation between single-genre vs multi-genre classification and average revenue.

Examine the trend of average revenue over time.

Explore how movie length impacts total gross income.

Identify the most voted movie genres based on user ratings.
 
 Data Sources
CSV File: Contains cleaned box office revenue data, including title, domestic_gross, and foreign_gross.

SQLite Database: Includes tables such as:

movie_basics: metadata (title, genre, runtime, release year)

movie_ratings: rating data (number of votes)

Others as needed for deeper insights

Tools and Technologies
Python

Pandas – for data manipulation

Seaborn & Matplotlib – for visualization

SQLite (via sqlite3) – for accessing structured movie metadata

Key Analyses Performed
Genre Analysis: Counted the number of genres per film to classify movies as Monogenre or Multigenre. Computed average total gross for each group.

Time Trend Analysis: Merged titles with release years to calculate the trend of average total revenue per year.

Runtime vs Revenue: Analyzed the relationship between movie duration and total gross income.

Genre Popularity: Used voting data to identify the most popular genres based on total number of votes.

Sample Visualizations
Bar plots comparing total average revenue for mono- and multi-genre films.

Line plots showing average revenue by release year.

Scatter plots of runtime versus total gross.

Bar charts of the top 10 most voted movie genres.

This analysis provides valuable insights into factors that influence a movie’s commercial success and viewer popularity. It can be used as a foundation for deeper machine learning models or as a standalone business intelligence report.
