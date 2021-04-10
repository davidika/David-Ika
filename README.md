
## A central page to summarise some of my projects, with links to repositories, code and publications.



# 1. Exploratory data analysis of crowdfunding data from Kickstarter
* GitHub repository [here](https://github.com/davidika/Analysis-of-Kickstarter-campaign-data).
* RPubs publication [here](https://rpubs.com/david_ika/EDA-kickstarter).
* Dataset [here](https://www.kaggle.com/codename007/funding-successful-projects).

This Project applies various methods to a dataset to clean, transform, visualise and report on observations.

The chosen dataset is titled "Funding Successful Projects on Kickstarter" and can be found on Kaggle [here](https://www.kaggle.com/codename007/funding-successful-projects), uploaded by user [Lathwal](https://www.kaggle.com/codename007)

The dataset was released by [Kickstarter](https://www.kickstarter.com/), a crowdfunding company that connects community investors with start-up projects in an 'all-or-nothing' fashion: The user sets a goal for their project, and if it falls short by even $1, zero funding is attained.

The data was initially released from the perspective of the company, in that it had an interest of predicting the success of a project. There is also, however, information that potential creators may find useful.




# 2. Predicting Kickstarter campaign success
* GitHub repository [here](https://github.com/davidika/Predictive-analytics-of-Kickstarter-campaign-data).
* RPubs publication [here](https://rpubs.com/david_ika/predicting-Kickstarter-campaign-success).

This project aims to address the initial business objective set by Kickstarter: to help predict whether a project will be successfully funded. Various classification and clustering methods will be used to achieve this.



# 3. Numeric analysis of CSV file
* GitHub repository (with source code and sample csv file) can be found [here](https://github.com/davidika/Numeric-analysis-of-CSV-file). 

A pythonic tool (importing no libraries) that processes a given CSV file, forms statistical information and outputs that information. User calls main(csvfile, year, type) such that they call the file, then the year of interest, and then whether they want info on general statistics (type = 'stats') or on correlations (type = 'corr').


# 4. Sentiment analysis of web pages
* GitHub repository (with source code) can be found [here](https://github.com/davidika/Sentiment-analysis-of-web-pages). 


A program to process WARC files and extract information from the HTML data within. The program analyses text to produce insights related to public sentiment, in several countries, towards their government. The user inputs 3 arguments: a WARC (web archive) file to be processed, a text file containing words defined as 'positive', and a text file containing words defined as 'negative'. The output produced is 4 lists: the first 3 being floats of statistics related to the counts of positive and negative words, and the last list being a list of the top-5 most occurring domain names in the file, along with their count.

