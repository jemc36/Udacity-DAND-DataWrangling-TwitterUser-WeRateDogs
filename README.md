# Web Scraping: Tweet Archive of Twitter User @dog_rates data analysis
I will be gathering data from three sources, including downloading file from Udacity, dowloading from url and web scraping from Twitter API.  

The project includes the following contents:  
* Introduction  
* Data gathering   
* Data assessing  
* Data Cleaning  
* Data Analysis and visualization
* Proposal for the next step  

### Language, Packages and Libraries  
The project is using Jupyter notebook with Python 3.7. The packages include numpy, pandas, requests, tweepy, json, timeit, re, matplotlib.pyplot, seaborn, and scipy.stats.

### Metadata
The definition of tweet data can be found on the [twitter website](  https://developer.twitter.com/en/docs/tweets/data-dictionary/overview/tweet-object.html)  

Image prediction is generated by neural network. The definitions of the variables are in the following table.

| Variable Name  | Definition                                                                                  |
|----------------|---------------------------------------------------------------------------------------------|
| tweet_id       | the last part of the tweet URL after "status/"                                              |
| p1             | the algorithm's #1 prediction for the image in the tweet                                    |
| p1_conf        | how confident the algorithm is in its #1 prediction                                         |
| p1_dog         | whether or not the #1 prediction is a breed of dog                                          |
| p2             | the algorithm's #2 prediction for the image in the tweet                                    |
| p2_conf        | how confident the algorithm is in its #2 prediction                                         |
| p2_dog         | whether or not the #2 prediction is a breed of dog                                          |
| p3             | the algorithm's #3 prediction for the image in the tweet                                    |
| p3_conf        | how confident the algorithm is in its #3 prediction                                         |
| p3_dog         | whether or not the #3 prediction is a breed of dog                                          |

### Methodology
* Descriptive Statistics
* Predictive Modeling (in development)

### Reports
* wrangle_act.ipynb includes all the process from data wrangling to data analysis.
* wrangle_report.ipynb: documentation for data wrangling steps: gather, assess, and clean
* act_report.ipynb: documentation of analysis and insights into final data

### Datasets
* twitter_archive_enhanced.csv: file as given
* image_predictions.tsv: file downloaded programmatically  
* tweet_json.txt: file constructed via API
* twitter_archive_master.csv: combined and cleaned data
* image_predictions_tp.csv: cleaned data
* Twitter.db includes cleaned data, twitter_archive_master.csv and image_predictions_tp.csv

### Feedback
* Udacity reviews
