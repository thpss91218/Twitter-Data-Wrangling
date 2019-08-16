# Twitter-Data-Wrangling
## Dataset
The raw data was collected from WeRateDogs Twitter account and it comes with two parts (1)Enhanced Twitter Archive and (2)Image Prediction. 
The first one recorded all the basic information like timestamp, tweet id, and the full url ect..,
and the second one used the neural network(CNN) to predict the breed of dogs on the tweets.
The additional data for the like and retweet number was collected through web scraping with twitter’s API, it’s stored in a file called tweet-json.txt.

## Wrangle Process
The whole data wrangling process include Gathering, Assessing and Cleaning.
In the first part, I read in all the files written above.
Then I documented some of the issues in it after assessing it programmatically and manually.
Lastly, I fixed all the issues through the define, code and test process.
