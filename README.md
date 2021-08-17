# video-game-sales

## Exploring Video Game Sales Across the World

## Introduction
In this project, we are working with video game sales across the world scraped by Gregory Smith. The data can be found [here](https://www.kaggle.com/gregorut/videogamesales) on Kaggle. 

**The purpose of this analysis is to answer the following business questions:**
1. How many games were released per year?
2. Based on sales, who are the top 10 publishers in each region?
    a. Compared the top 10 publishers’ sales for 2 regions
    b. Compared 2 publishers’ sales for each region
3. What are the most popular genres for each publisher?
4. Dependent on the publisher, what are their sales over time?
5. What are the most popular genres for each region?
6. Are there any correlations with region sales?
7. Dependent on the genre, what are the most common words used in game titles?
8. Which platforms had the most video games available and the most video game sales?
9. Per year, which publisher released the most games?
10. Per year, which publisher had the most sales?
11. What are the top 5 games for each genre?

## Market Understanding
Insert market info about gaming industry

## Methods
- Data Visualization
- Data Cleaning
- Data Manipulation

## Technologies
- Python
    - pandas
    - numpy
    - matplotlib
    - seaborn
    
## About the data
As mentioned before, the data was scraped by Gregory Smith and the webscraper can be found [here](https://github.com/GregorUT/vgchartzScrape). The data has 16598 rows and 11 columns. This data only covers sales in North America, Europe, and Japan exclusively. All other countries are included in other sales and global sales.

Description of the columns:
- **`Rank`** - Ranking of overall sales
- **`Name`** - The games name
- **`Platform`** - Platform of the games release (i.e. PC,PS4, etc.)
- **`Year`** - Year of the game's release
- **`Genre`** - Genre of the game
- **`Publisher`** - Publisher of the game
- **`NA_Sales`** - Sales in North America (in millions)
- **`EU_Sales`** - Sales in Europe (in millions)
- **`JP_Sales`** - Sales in Japan (in millions)
- **`Other_Sales`** - Sales in the rest of the world (in millions)
- **`Global_Sales`** - Total worldwide sales

## Notebooks Referenced
- https://www.kaggle.com/amritachatterjee09/video-game-sales-eda-with-plotly
- https://www.kaggle.com/snanilim/video-games-sales-analysis-and-visualization
