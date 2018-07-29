# A billion dollar deal

Successfully predict the social media effect on stock market. The
stock price dropped after negative tweet increased.
Limitations:
- Twitter Crawler: Due to slow response from Twitter, it takes
hours to get data on a single company.
- Sentiment Analysis: Could use more data

<img src="examples/stopsign_result.png" alt="stopsign_result" height="250px" width="250px"> <img src="examples/dumpling_result.jpg" alt="dumpling_result" height="250px" width="250px"> <img src="examples/hamburger_result.png" alt="hamburger_result" height="250px" width="250px">


## Introduction

The goal of this project was to compare positive and negative statements posted on twitter and comparing them to effects they could have on the stock market.

***Beaware if you want to reproduce the result of this project, it may take hours to days to get the twitter data, since the offical API has restriction, we used 'Get-Old-Tweets-Programatically'. If you want to replot the result, all the data is avaliable in this repo.***

Key Events:
1. Snapchat stock loses $1.3 billion after Kylie Jenner tweet  (Feb 21, 2018)
2. Elon Musk Sent His Tesla to Space (Feb 6, 2018)
3. United airlines scandal, beat passenger (April 9, 2017)


## Pipline

1. Data Acquisition & Preprocessing:

	get stock data
	      
	get twitter data
	      
	sentiment analyze on twitter data

2. Data Visulization:

	plot&visulization


## Data Acquisition & Preprocessing

Data acquisition & preprocessing was done in the following folders:

```
twitter_crawler
stock_crawler
twitter_analyzer
```

In the ***readme.md file in each folder***, there are comprehensive guidlines on how to install reuse use the files. All the files and functions are well documented and support 'help' commend.

All the desired data are stored in the following folders.

```
twitter_data
stock_data
semtiment_data
```

## Data Visualization
Data Visualization part code and result are shown in jupyter notebook 'Visualizaton.ipynb'. 
(We cannot open jupyter notebook online in this Gitlab, so better download for more information)
for more use for plot functions, you can look at 'compilation tools', 'plot_df.py' and 'piechart.py'.

To plot poular hashtag bar graph, use twitter_analyzer/getpopular_hashtags.py.  Execute the
file with the United_Airlines_2017-04-04 to United_Airlines_2017-04-04  csv's in the same directory.  The outputed
csv can then executed on using plot_hashtag_bar.py, which will output the plot.