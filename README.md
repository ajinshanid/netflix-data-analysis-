# Netflix Data Analysis

## Overview

This project provides a basic exploratory data analysis (EDA) of the Netflix Movies and TV Shows dataset, which contains information about movies and TV shows available on Netflix. The analysis is performed in a Jupyter Notebook and includes data loading, data cleaning, visualization, and some key insights into the distribution of content types and countries represented on Netflix.

## Dataset

- **Source:** [Kaggle: Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File name:** `netflix_titles.csv`
- **Features include:**
  - `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

## Project Structure

- `Netflix_Basic_Analysis.ipynb`: Main Jupyter notebook with code and visualization.
- `netflix_titles.csv`: The dataset file (not included in this repo; download from Kaggle).
- `README.md`: Project documentation (this file).

## Key Steps in the Analysis

1. **Import Required Libraries**
    - `pandas`, `matplotlib`, `seaborn`
2. **Load the Dataset**
    - Read the CSV file into a pandas DataFrame
3. **Data Cleaning**
    - Handle missing values (e.g., fill or drop nulls)
    - Remove duplicates if any
    - Convert categorical features to appropriate types
    - This step ensures the data is consistent and ready for accurate analysis.
4. **Initial Exploration**
    - Inspect the first few rows, understand the schema and check for remaining missing values
5. **Visualizations**
    - Content Type Distribution: Bar chart (Movies vs TV Shows)
    - Top 10 Countries: Horizontal bar chart of countries with the most content


## Requirements

- Python 3.x
- Jupyter Notebook or Google Colab
- Libraries:
  - pandas
  - matplotlib
  - seaborn


## Insights & Possible Extensions

- Explore popularity trends by year or region.
- Analyze directors, actors, or ratings.
- Build recommendation engines or perform sentiment analysis on descriptions.


## Summary

This project provides a beginner-friendly analysis of the Netflix Movies and TV Shows dataset using Python. The Jupyter notebook walks through essential data cleaning steps to handle missing values and inconsistencies, ensuring a reliable foundation for analysis. It explores content types, popular genres, and the countries most represented on Netflix.
