
# Data-Wrangling-project-DAND
Licensing, Authors, and Acknowledgements
<li><a href="#Installation">Installation</a></li>
<li><a href="#Project Motivation">Project Motivation</a></li>
<li><a href="#File Descriptions">File Descriptions</a></li>
<li><a href="#Licensing, Authors, and Acknowledgements">Licensing, Authors, and Acknowledgements</a></li>


<a id='Installation'></a>
# Installation:
Python versions 3.*.
- Libraries:
- Pandas.
- numpy.
- matplotlib.
- seaborn.

<a id='Project Motivation'></a>
# Project Motivation:
"The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage."




<a id='File Descriptions'></a>
# File Descriptions:

"Our tasks in this project are as follows:

*Data wrangling, which consists of:
*Gathering data (downloadable file in the Resources tab in the left most panel of your classroom and linked in step 1 below).
*Assessing data
*Cleaning data
*Storing, analyzing, and visualizing your wrangled data
Reporting on 1) your data wrangling efforts and 2) your data analyses and visualizations
Gathering Data for this Project
Gather each of the three pieces of data as described below in a Jupyter Notebook titled wrangle_act.ipynb:

The WeRateDogs Twitter archive. I am giving this file to you, so imagine it as a file on hand. Download this file manually by clicking the following link: twitter_archive_enhanced.csv

The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. This file (image_predictions.tsv) is hosted on Udacity's servers and should be downloaded programmatically using the [Requests](https://2.python-requests.org//en/master/) library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv

Each tweet's retweet count and favorite ("like") count at minimum, and any additional data you find interesting. Using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's [Tweepy](http://www.tweepy.org/) library and store each tweet's entire set of JSON data in a file called tweet_json.txt file. Each tweet's JSON data should be written to its own line. Then read this .txt file line by line into a pandas DataFrame with (at minimum) tweet ID, retweet count, and favorite count. Note: do not include your Twitter API keys, secrets, and tokens in your project submission".


<a id='Licensing, Authors, and Acknowledgements'></a>
# Licensing, Authors, and Acknowledgements:
[The data in this repository comes from the Data analyst Nanodegree program](https://www.udacity.com/course/data-analyst-nanodegree--nd002).





