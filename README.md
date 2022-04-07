# capstone-data

Emails:
    enron-emails - 1.43 GB
	source: https://www.kaggle.com/datasets/wcukierski/enron-email-dataset
    emails-spamclass - 31.24 MB
	source: https://www.kaggle.com/code/balaka18/email-spam-classification/data
    spambase - unsure atm
	source: https://archive.ics.uci.edu/ml/machine-learning-databases/spambase/'

Stocks:
    I got all the data from https://www.alphavantage.co , which has a free API to get historical stock data. I'm going to use data from $QQQ's 1min, 5min charts and possibly more should I see fit. I'm also using various EMA (Exponential Moving Average) values.

    I've collected data from two different parts of the API:
	a) Intraday (extended history) - For every datapoint: time, open, high, low, close, volume
	b) EMA - for every datapoint: time, EMA
	
    I still have to merge the data, but doing a merge around the timestamp shouldn't be complicated


Drinks:
    I got photos of vodka, whiskey, and tequila from Bing Image Search from Microsoft Azure.
    bingimg - the code I used to gather the photos
    alcohol.zip - folder containing a folder of each drink's photos - ran out of space in Git large file storage

 
