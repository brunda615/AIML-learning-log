# Week 1: Exploratory Data Analysis 

## Overview
Exploratory data analysis and cleaning of the Netflix Movies and TV Shows dataset (8,807 titles) — practicing NumPy, Pandas, and data visualization fundamentals.

## Dataset
Source: Kaggle - Netflix Movies and TV Shows (Shivam Bansal)

## Key Steps
- Handled missing values: ~30% missing in `director`, ~9% in `cast`/`country`, filled as "Unknown"
- Parsed and cleaned `date_added` (stripped whitespace, converted to datetime)
- Split `duration` into numeric value + unit (minutes/seasons)
- Exploded multi-value `listed_in` genre field for genre-level analysis
- Verified [X] duplicate records (state your actual number)

## Key Findings
- [Fill in: Movie/TV split %]
- [Fill in: top country and % share]
- [Fill in: top genre]
- [Fill in: sharpest year of content growth]
- [Fill in: most common rating]

## Files
- `eda.ipynb` — full analysis notebook
- `data/netflix_titles.csv` — raw dataset
- `data/netflix_titles_cleaned.csv` — cleaned dataset
