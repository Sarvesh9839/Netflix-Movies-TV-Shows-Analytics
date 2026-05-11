# Netflix-Movies-TV-Shows-Analytics
Netflix-Movies-TV-Shows-Analytics

Netflix-Movies-and-TV-Shows-Analysis
Table of Contents
1. About the project

2. About the dataset

3. Tools and libraries

4. Phases of the project

4.1. Data Exploration

4.2. Data Cleaning

4.3. Data Analysis and Visualization

About the project
This project is a self-study project, its main objective is to help me practice on a real dataset and strength my analysis skills in Python.

It is about cleaning and analyzing Netflix movies and tv shows data, and getting insights about the countries where they were filmed, their ratings and release years.

The detailed notebook of the project is here.

About the dataset
This project's dataset is an open-source data from Kaggle.

You can find it here.

The dataset contains one "csv" file which has 7787 entries with the following information:
Type: Movie or TV Show
Title: The name of the movie/tv show
Director
Cast: The names of the movie/tv show's cast
Country: The country(s) which this movie/tv show was filmed
Date added: The date when the movie/tv show was added on Netflix
Release year
Rating: Age-based media reviews
Duration: The number of minutes for movies or number of seasons for tv shows
Listed in: The category(s) which this movie/tv show is listed in
Description: A sentence which describes this movie/tv show on Netflix
Tools and libraries
This project was done in Python using Jupyter Notebooks.

The libraries used are:

Pandas and Numpy: for exploration, cleaning and analysis
Matplotlib and Seaborn: for visualizations
Phases of the project
1. Data Exploration
After reading the data I have to explore it, its columns, and the info it contains. So, I've gained information about:

The dataset size
The datatypes of the columns
What each column represents
What are the information inside the categorized columns such as type, listed_in, rating and country.
2. Data Cleaning
After exploring the data, I need to check it if there are any issues.

Search for duplicates

Fortunately, it has no duplicates.
Search for nulls

2.1. Columns with few nulls

Solution 1: Get the missing information by searching for them
Solution 2: Drop them
2.2. Columns with many nulls

Solution: I wasn't interested in those columns so I left them as they're
Change the incorrect datatypes into appropriate datatypes
