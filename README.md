# Yelp Dataset (2017) Sentiment Analysis - Predicting Review Star Ratings
This repository contains a trimmed down and simplified version of the original notebook for the course INM430 Principles of Data Science, at City, University of London.  
The Yelp Review dataset in json format can be downloaded from [Yelp]( https://www.yelp.com/dataset/challenge) and the sentiment lexicon from [Hu, Minqing and Bing Liu (2004) ](http://www.cs.uic.edu/~liub/FBS/opinion-lexicon-English.rar). It is recommended to use a small sample of the complete dataset. A quick way is to use unix command line tools, e.g.  
`head -10000 review.json >> review_10k.json`  
The original dataset is not ordered so we can take the first 10k lines as a sample.
