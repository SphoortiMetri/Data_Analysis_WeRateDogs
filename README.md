# Data_Analysis_WeRateDogs

This project focuses on 

1. Gathering data from various sources 
2. Identify assess and clean quality and tidiness issue with data 
3. Analyze and provide insights 


#### The Data
#### Enhanced Twitter Archive

The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though: each tweet's text, which I used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." Of the 5000+ tweets, I have filtered for tweets with ratings only (there are 2356).

#### Extracted data from tweet text
The extracted data from each tweet's text

- Assess and clean this data 

#### Additional Data via the Twitter API

Gather more data from corresponding tweet_ids using twitter API

#### Image Predictions File

A table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).


#### What software do I need? 

1. pandas
2. NumPy
3. requests
4. tweepy
5. json
