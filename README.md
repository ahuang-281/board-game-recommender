## This repository covers the development of a board game recommendation engine from start-to-finish.  The documents and notebooks for this project are described below, in order.
#### Skill keywords:  Web Scraping, Data Wrangling, Exploratory Data Analysis, Collaborative Filtering, Machine Learning, k-Nearest Neighbors (kNN), Singular Value Decomposition (SVD)
## [proposal.pdf](https://github.com/ahuang-281/board-game-recommender/blob/master/proposal.pdf)
This PDF introduces the motivation behind the project and details data gathering and analysis methods to be used in the project.
## [bgg-data-scrape.ipynb](https://github.com/ahuang-281/board-game-recommender/blob/master/bgg-data-scrape.ipynb)
This Jupyter Notebook contains the code for gathering board game information and ratings from boardgamegeek.com using a combination of web scraping and requesting data from their public API.
## [bgg-data-clean.ipynb](https://github.com/ahuang-281/board-game-recommender/blob/master/bgg-data-clean.ipynb)
This Jupyter Notebook contains the code for trimming the dataset of games or users with low numbers of ratings.  The ratings are then organized into a "long" data format for later input into the predictive models.
