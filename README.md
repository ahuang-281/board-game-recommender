## This repository covers the development of a board game recommendation engine from start-to-finish.  The documents and notebooks for this project are described below, in order.
#### Skill keywords:  Web Scraping, Data Wrangling, Exploratory Data Analysis, Collaborative Filtering, Machine Learning, k-Nearest Neighbors (kNN), Singular Value Decomposition (SVD)
## [proposal.pdf](https://github.com/ahuang-281/board-game-recommender/blob/master/proposal.pdf)
Introduction and motivation behind the project. Data gathering and analysis methods to be used in the project are suggested.
## [bgg-data-scrape.ipynb](https://github.com/ahuang-281/board-game-recommender/blob/master/bgg-data-scrape.ipynb)
Code for gathering board game information and ratings from boardgamegeek.com using a combination of web scraping and requesting data from their public API.
## [bgg-data-clean.ipynb](https://github.com/ahuang-281/board-game-recommender/blob/master/bgg-data-clean.ipynb)
Code for trimming the dataset of games or users with low numbers of ratings.  Ratings are organized into a "long" data format for later input into predictive models.
## [bgg-data-story.ipynb](https://github.com/ahuang-281/board-game-recommender/blob/master/bgg-data-story.ipynb)
An exploration of interesting trends observed in the cleaned BGG data set.
## [bgg-data-interactive.ipynb](https://github.com/ahuang-281/board-game-recommender/blob/master/bgg-data-interactive.ipynb)
An interactive visualization for comparing ratings between 2 users.  Figures included to demonstrate examples for good and bad collaborative predictors for item ratings.
