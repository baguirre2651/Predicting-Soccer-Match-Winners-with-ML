# Predicting-Soccer-Match-Winners-With-ML
Creating a Machine Learning Model to Predict the Outcome for La-Liga Soccer Matches based on Data Scrapped from Past 3 Seasons.

Project Overview:

Skills: Python3, Machine Learning, Random Forest Classifier Algorithm, Data Scraping, Jupyter Notebook 

Imports: Beautiful Soup, Pandas, Random Forest Classifier,


Phase 0: Picking the Data
    
    -My Favorite Soccer Team is F.C Barcelona 
    and so I decided to use Data from https://fbref.com/en/comps/12/La-Liga-Stats 
    of the past 3 seasons (2018-2023) to collect my data to use for my model I will be creating. 



Phase 1: Data Scraping 
    
    -Because Data is messy and unorganized, 
    I scraped the Data from past 3 seasons 2018-2023 to
    better extract and prepare it for the model to read information efficently. 
    
    -Started off with getting standings url for the La-Liga season from FBREF.com
    -used Beautiful Soup import to take in the data text from Fbref.com to visualize it better
    -Extracting URL and HTML Statistics into our Data from Each Team. 
    -Using Pandas Import to Read table out of HTML and making it into a data frame 
    -Scaped Data out of the table in the standings page and to get each individual squad page into our data.
    -Then Scraped to get Scores and Shooting stats for each Match.
    -Combined all the data frames together.
    -Make a loop to go through the past seasons data for each year and for each team and then scrape the data into a single data frame
    -Turned data into a csv called "Matches.csv"
    

Phase 2: Creating our Model 
   
    Used Our Scraped Data from the past 3 la liga seasons 2018-2019, 2020-2021, 2022-2023.
    -Used a Random Forest Classifier to create a model that takes in the data from the sets in order to make predictions on outcomes and compare actual results.
    -Used Predictors from the data given to train our targeted model. 
    -Increased Precision and Accuracy from the model by creating new predictors and using the rolling averages and combining --
    -Each the object to increase prescision and accuracy.
    -Taken into the matches played in September our model has an accuracy of 93% and prescion of about 95%, when looking at the combined data frame. 
