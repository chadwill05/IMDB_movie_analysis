# IMDB_movie_analysis

IMDb Top 10,000 Movies Analysis
Overview
Movies have always been a source of joy, entertainment, and reflection for many. Personally, I find solace in them. They are my escape from the hustle and bustle of daily life. This project is a manifestation of my love for movies. Dive in with me as I navigate through this dataset and unravel some interesting insights.

Objective

This analysis revolves around the IMDb's top 10,000 movies, looking to:

Uncover distribution trends over the years based on various attributes like certification and genre.
Dive deep into runtimes, ratings, and other facets of movies to uncover evolving patterns.
Visualize the data in intuitive charts that bring clarity to the complex world of cinema.

Dataset

The dataset comes from IMDb, covering the top 10,000 movies. The dataset boasts attributes such as:

Title
Release Year
Runtime
Certificate
Genre
Director
Stars
Rating
Metascore
Votes
Gross Revenue

Tools and Libraries Used

Google Colab: Leveraged for interactive Python programming and data analysis.
Pandas: A staple for data manipulation and analysis.
Matplotlib, Seaborn, Plotly: Visualization libraries that bring data to life.
Regular Expressions (re): For string operations and data cleaning.

Key Findings

A considerable number of movies lack data on certificate, metascore, and gross, which suggests gaps in data collection or reporting over the years.
The dataset reveals a variety of movies, spanning from all-time classics like "The Shawshank Redemption" and "The Godfather" to lesser-known films.
There's an evident change in movie certification and genre distribution over the years.
The average runtime of movies has shown fluctuations, giving insights into evolving audience preferences.

Methodology

The steps taken in this analysis include:

Data Import and Cleaning: Imported data from CSV, identified null values, and processed certain columns for more structured data.
Exploratory Data Analysis (EDA): Used descriptive statistics and visualizations to understand the dataset's structure and underlying patterns.
Data Visualization: Created a plethora of charts using Plotly, diving deep into the distribution of years, certificates, genres, and more.

Future Work
Given the rich dataset, there's potential for further deep dives:

Analyze the top directors and actors in terms of ratings, revenue, and votes.
Establish potential correlations between ratings and gross revenue.
Dive deeper into the critical acclaim of movies, relating rating with metascore.
Consider machine learning techniques to predict ratings based on other movie attributes.

