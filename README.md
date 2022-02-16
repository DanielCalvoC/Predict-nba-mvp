# Predict NBA MVP : Web scraping and ML project
I am trying to predict who is going to be the MVP in a given NBA season. For this, I'll use NBA data on www.basketball-reference.com. This project has 3 big parts: web scrapping, data cleaning and machine learning

Usage
--------
Jupiter Notebook 

Description
--------
WEB SCRAPING:

Download MVP votes with requests

Parsing the votes table with BeautifulSoup. Extract the data from each html

Combining MVP votes with Pandas --> mvps.csv

Download player stats

Using Selenium to scrape a Javascript page

Parsing the stats with Beautifulsoup

Combining player stats with Pandas --> players.csv

Downloading team data

Parsing the team data with Beautifulsoup

Combining team stats with Pandas --> teams.csv


DATA CLEANING:

Cleaning player data

Combining the player and mvp data --> combined dataframe

Cleaning the team data

Combined data frame and teams df

Exploring data and looking for correlations


MACHINE LEARNING:

Prepare data

Training ML model: Ridge regression

Identifyng an error metric -- evaluate if this algorithm do a good job

Implementing backtesting to predict each year

Diagnosing model performance

Adding more predictors

Using a random forest




Used tech
--------
- Python
- pandas
- Beatiful Soup
- Selenium
- matplotlib
- sklearn - Ridge regression, RandomForest
