# Wrangle-and-analyze-data

## About

The dataset provided by Udacity is the tweet archive of twitter user known as WeRateDogs or @dog_rates. WeRateDogs is a twitter account that rates people’s dogs.

## Project Aim
This project aims at wrangle the twitter data through; • Gathering Data
• Assessing Data
• Cleaning Data
And then analyze and visualize the wrangled data. Finally, report on the data wrangling project and data analysis.

## Data Wrangling process:
### 1- Gathering Data
- CSV File
- Scrape from a website and saved as TSV file
- Scraped tweets using twitter API

### 2- Assessing Data
- Quality Issues
- Tidiness Issues

### 3- Cleaning Data
- I have created a copy of each dataframe, which in this case 3 dataframes
- Merged the copied dataframe into one.
- Created a new column called dog_type, it contains various dog types like: doggo, floofer, pupper and puppo.
- Drop unwanted columns and also columns with missing values. • Changed Tweet_id from int to string
- Changed Name into string type
- Changed timestamp into date time format
- Extracted from the dataset a new feature which is dog ratings.

## Conclusion 
The results of the analysis over WeRateDogs account. Our analysis tells us which kinds of dogs are popular in adoption, what dog names are popular, and also valuable information about WeRateDogs account,their followers' favorite tweet actions such as liking or retweeting, and their tweets activity over time.

- Followers’ tends to like tweets over retweeting
- Popular dog name is Charlie
- Popular dog type is Pupper
- Their Tweets have sharply decreased over time
