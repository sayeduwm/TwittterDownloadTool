# TwittterDownloadTool
**Downland Historical twitter using web-scraping.**

This tool can be used with or wothout Twitter API.

Without twitter API: this tool is able to download all the elements of the tweets displayed on screen ( including twitter ID) using webcraping techniques

With Twitter API: collect all the elements of a Tweet.

Download all the files in a directory and then follow the following steps:

Block 1: Import all the necessary libraries

BLock 2: Provide Twitter API information

Block 3: The method "scrapTweet" takes standard query as input and provide a list of twitter IDs.

Block 4: The custom methods to generate query from words.

Block 5: Provide csv files: (1) birgrams related to tweets and (2) city( to collect Tweets by states).

Block 6: Collect tweet IDs based on the bigrams and city names using the query like     #"construction zone" (wisconsin, OR WI, OR chicago, OR milwaukee).

Block 7: Save the collected Tweet IDs in a csv file

BLock 8: Collect all the tweet elemengts for the collected tweet IDs using Twitter API.
