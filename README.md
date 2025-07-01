📊 Netflix Movie Data Analysis Project

🧠 Overview

Netflix is known for its extensive use of data science, artificial intelligence, and machine learning to deliver personalized viewing experiences. In this project, we analyze a dataset of over 9,000 Netflix movies to extract meaningful insights that can help in strategic decision-making.

🔍 Exploration Summary

The dataset consists of 9,827 rows and 9 columns.

The data is clean, with no missing (NaN) or duplicate values.

The release_date column should be converted to datetime format, and the year extracted for analysis.

Columns such as overview, original_language, and poster_url are not useful for current analysis and can be dropped.

There are outliers in the popularity column that need to be addressed or visualized carefully.

The vote_average column should be categorized (e.g.,popular,average,below_avg,not_popular) for better aggregation.

The genre column contains comma-separated values with white spaces that need cleaning and transformation for genre-wise grouping.


🎯 Objectives

The aim of this project is to answer key business questions through Exploratory Data Analysis (EDA), such as:

What is the most frequent genre of movies released on Netflix?

Which genre has the highest votes in the vote average column?

What movie got the highest popularity, and what's its genre?

What movie got the lowest popularity, and what's its genre?

Which year had the most movies filmed?

📈 Summary of Analysis

Question	Insight

Q1: Most Frequent Genre	🎭 Drama is the most frequent genre in the dataset, appearing in over 14% of the entries among 19 genres.

Q2: Genre with Highest Votes	🗳️ Drama again stands out with the highest vote share, accounting for 18.5% of the most popular movies among the top 25.5% of the dataset (6,520 rows).

Q3: Highest Popularity Movie	🚀 "Spider-Man: No Way Home" has the highest popularity in the dataset, with genres: Action, Adventure, and Science Fiction.

Q4: Lowest Popularity Movie	🧊 "The United States, Thread" has the lowest popularity, with genres: Music, Drama, War, Sci-Fi, and History.

Q5: Year with Most Movies	📅 The year 2020 had the most number of films released in the dataset.

🗃️ Dataset

📦 Records: 9,000+ Netflix movies

📊 Features may include: title, genre, vote_avg, popularity, release_year, and more.

🛠️ Tools & Technologies
Python

Pandas, NumPy – data wrangling

Matplotlib, Seaborn – visualization

Jupyter Notebook – interactive analysis
