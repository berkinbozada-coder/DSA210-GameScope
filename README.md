# DSA210-GameScope
# GameScope: Predicting Video Game Success from Market and Review Data

DSA 210 – Introduction to Data Science
Berkin Bozada

## Project Motivation
My name is Berkin Bozada and I really love playing video games. This kind of finding best video games in order to make myself happy is really important situation for me. That's why this project aims to explore what makes a video game successful by analyzing factors such as price, genre, release year, platform-related features, and user review information.

## Research Question
Can video game success be predicted using market, genre, and review-related features?

## Planned Methods
- Data collection
- Data cleaning
- Exploratory data analysis
- Hypothesis testing
- Machine learning modeling
- Data visualization

## Repository Structure
- data/: raw and processed datasets
- notebooks/: Jupyter notebooks for analysis
- figures/: visual outputs and plots
- scripts/: helper scripts and utility code

# Data Sources

## Planned Main Dataset
- Steam Store Data (Kaggle): includes pricing, discount, and review-related variables.

## Planned Supporting Dataset
- Steam Games Dataset (Kaggle / Steam API + Steam Spy): includes metadata such as genre and release information.

## Planned Enrichment
The datasets will be merged and enriched through feature engineering, including:
- game_age
- genre_count
- positive_review_ratio
- price_category
- success_level

- # Data Sources

## Main Dataset
- steam.csv  
Contains core game-level information such as release date, genres, tags, ratings, playtime, owners, and price.

## Enrichment Dataset
- steamspy_tag_data.csv  
Contains tag-level information for Steam games and will be used for feature enrichment.

## Current Progress
- Project proposal completed
- Raw datasets uploaded
- Cleaned dataset created
- Exploratory data analysis completed
- Hypothesis testing completed for the April 14 milestone
