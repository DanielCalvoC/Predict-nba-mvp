# Predict NBA MVP : Web scraping and ML project
I am trying to predict who is going to be the MVP in a given NBA season. For this, I'll use NBA data on www.basketball-reference.com. This project has 3 big parts: web scrapping, data cleaning and machine learning

![This is an image](https://library.sportingnews.com/styles/crop_style_16_9_desktop/s3/2021-08/michael-jordan_yzt70lkmipqq19lqklwtwpeu3.png?itok=pustlDga)

Usage
--------
Jupiter Notebook  Predict-NBA-MVP-Web-scraping-and-ML-project.ipynb

Description
--------
Web scraping: I'll download the NBA data I need.  To do the scraping, I'll use python, with the selenium, beautifulsoup, pandas, and requests libraries.  I'll download the files using requests and selenium, then parse them with beautifulsoup and load them into pandas DataFrames. By the end, I'll have csv files that we can then merge and use to make predictions.

Data cleaning. I'll combine our mvp, player, and team stats data using pandas.  Along the way, I'll work through a lot of data cleaning, including using merge, map, fillna, and replace.  I'll also use matplotlib to explore the data. By the end, I'll have a clean DataFrame that I can use for machine learning.

Machine learning to predict who will win MVP each year.  I'll first prepare the data for machine learning and use a Ridge Regression model.  I'll then define an error metric, backtest across most of the data set, and iterate on our predictors.  I'll end by using a Random Forest model to make predictions.


Used tech
--------
- Python
- pandas
- Beatiful Soup
- Selenium
- matplotlib
- sklearn - Ridge regression, RandomForest
