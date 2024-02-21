# web-scrapper
Application for Scrapping data from web/ social media platforms

Project 01 within web-scrapper : Fetching data from Twitter using python.
* In order to scrape data we are going to use Scraperapi (url : https://www.scraperapi.com/ )
* Create an account on scraperapi
* Fetch the API key in order to use it in our project
* Open Jupyter Notebook
* We will need import two libraries : 'import requests' and 'import pandas as pd'
* requests : we'll be using to make sure HTTP requests to actually go out to the web and scrape data
* pandas : using this because once we scrape our data and get that data back we'll be using 'data frames' so that we can look at our data and then have access to all of the pocessing fuctions that you can use with pandas
* create a blank list and append our data into this list
* create payload set that will contain parameters that will dictate how our search works, so the first thing we'll pass in is the 'API key', then we will pass in the 'query' which is the keyword we are looking for, then we will pass 'num' or the number of results we are expecting (tweets we want to scrape)
* the we will create response and set it as get request, also tell what our parameters(params) are which is equal to payload
* we will create variable 'data' which will store the 'response' which we get in json format
* we can 'data.keys()' to see the keys which can filter out with
