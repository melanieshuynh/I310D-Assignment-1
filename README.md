# I310D-Assignment-1
Repository for I310D Assignment 1: Data Collection and Curation.

# Project Goal
The goal of this project was to collect data using the Twitter API and create visualizations utilizing the information gathered. As it pertains to my project, with the announcement of the new Zelda title on 9/13/22, I was curious about the fluctuation and trends in metrics (likes, retweets, replies, quote retweets) over the course of 10 days, from 9/08/22 to 9/18/22.

# API Documentation:
https://developer.twitter.com/en/docs/twitter-api 
https://developer.twitter.com/en/docs/tutorials/postman-getting-started
https://documenter.getpostman.com/view/9956214/T1LMiT5U

# MIT License, Twitter Developer Agreement 
Copyright <2022> <Melanie Huynh>
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
https://developer.twitter.com/en/developer-terms/agreement-and-policy

Source data pulled directly from Twitter.
  
# Data Type and Attributes
public_metrics/retweet_count: (int) number of retweets a single post ID received 
public_metrics/reply_count: (int) number of replies a single post ID received 
public_metrics/like_count: (int) number of likes a single post ID received 
public_metrics/quote_count: (int) number of quote retweets a single post ID received 
text: (str) the caption/text content of the tweet created by the poster for a single post ID
id: (int) unique Twitter ID user 
created_at: (int) date of creation

# Potential Issues
Utilized Twitter Advanced Search to collect data on the first 5 posts for the date inputted, which could be randomized or shown in a different order when using Twitter's Advanced Search feature. Sources of bias/error could include Twitter's internal search algorithms and pulling data manually for each post ID.


