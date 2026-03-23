# Project Proposal

## Project Title
GameScope: Predicting Video Game Success from Market and Review Data

This project aims to investigate which factors are associated with the success of video games and whether game success can be predicted using market and review-related features. Video games differ in terms of genre, price, release date, player reception, and popularity, and these differences may help explain why some games become more successful than others.

The main dataset for this project will be the publicly available `steam.csv` dataset, which includes game-level variables such as game name, release date, genres, Steam tags, positive ratings, negative ratings, average playtime, owners, and price. In order to satisfy the enrichment requirement for public datasets, I will also use `steamspy_tag_data.csv` as a supporting dataset to enrich the main data with tag-level information. Additional supporting files such as description or requirements data may be used later if needed.

The data will be collected from publicly available CSV files and loaded into Python using pandas. After collection, the dataset will be cleaned by handling missing values, removing duplicates, standardizing selected fields, and creating additional variables such as release year, game age, total review count, and positive review ratio. The main dataset contains around 27,000 game records, while the tag dataset contains tens of thousands of rows and a large set of tag-related variables.

The project will include exploratory data analysis, data visualization, hypothesis testing, and machine learning methods. The main goal is to identify which variables are most strongly related to game success and to evaluate whether video game success can be predicted using price, ratings, release information, playtime, ownership, and tag-based features.
