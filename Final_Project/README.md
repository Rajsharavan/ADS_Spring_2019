# Fake News Detection
Our goal is to explore how artificial intelligence technologies, particularly machine learning and natural language processing, might be leveraged to combat the fake news problem. We believe by using these technologies we can automate and help the users to determine if a story is real or hoax.

## Project Proposal
https://codelabs-preview.appspot.com/?file_id=1u2F1msab5EDgI3fw8woNHvoOiINpP_Try43XpodiPVo#0

## Report

https://codelabs-preview.appspot.com/?file_id=1xd8vRCw9T6i-hWz2pGcYMlJ7LkAFHb_A_MvVtdYpP_w#0

## Presentation Link

https://docs.google.com/presentation/d/1jFdPH0L-jbc2sboGsu5Tg3Jp6L2KdibOsiwRgi9ihio/edit?usp=sharing

## Before execution install below libraries:
•	pandas

•	numpy

•	matplotlib

•	LabelEncoder

•	train_test_split

•	CountVectorizer

•	TfidfVectorizer

•	svm

•	metrics

•	ConfusionMatrix

•	pyplot

•	f1_score

•	roc_auc_score

•	os

•	sklearn

•	seaborn

•	itertools

•	nltk

•	string

•	re

## Instructions to execute files :

### (Step 1) : Web Scraper
Scrapes data from 3 reputed newspapers and fake news to collect data into different csvs.

### (Step 2) : Data Processing
Merges all the data into one dataset 'Final_data.csv'. 
Perform an exploratory data analysis on this dataset with file (03_Exploratory Data Analysis.ipynb)

Execute code under data cleaning in data processing file (02_Data_Processing.ipynb)
Cleans this data to handle the missing values, null values and any unwanted data to give a cleandata.csv file

Perform exploratory data analysis on the cleaned dataset (04_Exploratory_Data_Analysis.ipynb)

### (Step 3) : Models
Generates different models and calculates metrics(F1 score, precision, recall, accuracy, error rate, confusion matrix and ROC Curve) for each of these models

### (Step 4) : Webpage with FLask
Creates a webpage for our model

### (Step 5) : Dockerisation
Docker image :

### (Step 6) : Hosting

