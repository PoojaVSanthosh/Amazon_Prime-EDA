# Amazon_Prime-EDA
Project Overview

This project focuses on analyzing Amazon Prime Video’s catalog of movies and TV shows using Exploratory Data Analysis (EDA). With increasing competition in the OTT industry, platforms like Amazon Prime must understand viewer preferences, content performance, and market trends.
This analysis helps uncover patterns, trends, and business insights by exploring dataset features such as genres, ratings, release years, and content distribution.

*Project Objective*: 
This project aims to analyze Amazon Prime Video's content catalog (TV shows and movies) through Exploratory Data Analysis (EDA). The core objectives are to understand the content's structure and characteristics, draw conclusions about what makes content successful, identify dominant genres, analyze rating variations, and understand how viewer preferences are reflected across different content types. The ultimate goal is to uncover insights that can influence subscription growth and content investment strategies in the streaming industry.

The dataset was created to list shows available on Amazon Prime streaming and analyse the data to find interesting insights and there are 2 type of datasets used that is available in US.

*Titles Dataset (titles.csv):* 
This dataset contains metadata for Amazon Prime movies and TV shows. It includes details such as a unique id, title, type (movie or show), description, release_year, age_certification, runtime in minutes, genres, production_countries, number of seasons (for shows), imdb_id, imdb_score, imdb_votes, tmdb_popularity, and tmdb_score.

*Credits Dataset (credits.csv):*
This dataset provides information about the cast and crew involved in the content. It includes person_id, the content id (linking to the titles dataset), name of the person, character played (if applicable), and their role (e.g., ACTOR, DIRECTOR).

*Technologies & Libraries Used*
The project is implemented in Python using:
1.Pandas – data cleaning, manipulation, filtering
2.NumPy – numerical operations
3.Matplotlib & Seaborn – data visualization

*Key EDA Insights*
1.Identifies the most dominant genres and content categories.
2.Analyzes trends in release year vs runtime, revealing how movie durations evolve over time.
3.Explores content distribution by ratings to understand platform diversity.
4.Visualizes relationships using bar charts, scatter plots, lineplots, and grouped summaries.
5.Provides insights valuable for researchers, analysts, and marketing teams in the streaming industry.

*Project Workflow*
1.Load and inspect datasets
2.Data cleaning (handling duplicates, missing values, dtype adjustments)
3.Univariate Analysis – distributions of ratings, genres, content types
4.Bivariate Analysis – runtime vs release year, genre trends, rating comparisons
5.Visualization & Interpretation
6.Business insights and actionable findings

*Conclusion*
This EDA project demonstrates how raw streaming data can be transformed into meaningful insights. Through structured analysis and visualization, we uncover patterns that help digital entertainment platforms make smarter decisions in content strategy, customer engagement, and competitive positioning.
