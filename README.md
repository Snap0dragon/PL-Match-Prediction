# PL-Match-Prediction
PL Match Prediction. Testing done on data of Premier League seasons 2020-23

# Project Introduction:
PL Match Prediction is a machine learning project aimed at predicting the outcomes of Premier League (PL) football matches. The project consists of two main components: (1) web scraping of match and team data, and (2) building and running a machine learning model to predict match outcomes based on historical data. This project showcases the end-to-end pipeline, from data collection through web scraping to training a predictive model.

# Project Files:
**1. 4710_OEL2_Web_scraping_data.ipynb:**
- Item 1 This notebook is responsible for scraping Premier League data from online sources. Using Python libraries such as requests and BeautifulSoup, the script collects match statistics, team standings, and other relevant data from websites like fbref.com.
- Item 2 Key steps include:
- Sub Item 1 Sending HTTP requests to retrieve the HTML content of the Premier League stats page.
- Sub Item 2 Parsing the HTML content to extract relevant match and team data.
- Sub Item 3 Cleaning and formatting the scraped data for use in the predictive model.

**2. 4710_OEL2_ML_MODEL.ipynb:**
- Item 1 This notebook contains the machine learning model used for predicting the outcomes of Premier League matches.
- Item 2 Key steps include:
- Sub Item 1 Exploratory Data Analysis (EDA): Visualizing the distribution of categorical and numerical variables such as team, venue, and match result.
- Sub Item 2 Model Training: Using historical match data to train a predictive model (e.g., regression or classification model).
- Sub Item 3 Model Evaluation: Assessing the performance of the model using metrics such as accuracy or F1 score.

# Use Cases:
- Item 1 Football Enthusiasts: Analyze and predict upcoming Premier League match outcomes based on historical performance data.
- Item 2 Data Science Practitioners: Learn how to integrate web scraping with machine learning to create an end-to-end data pipeline.
