# twitter_scraping_zapier
Twitter scraping for Zapier

This is a project for Twitter scraping for Zapier to verify the lexicon used in the realm of Twitter as a particular social media platform.
It also involves the creation of unigrams and bigrams frequency distributions (and trigrams in future). 
____________________________________________________

Data was obtained from Twitter in the following timelines for search term "zapier" on Twitter's platform:
- 2016
- 2017
- 2018
- 2019 YTD (Mid Nov 2019)

Special thanks to Python package GetOldTweets3.
_____________________________________________________

Following work has been completed:
- Unigrams: 
    -- Unigrams tokens with sorted frequency distribution for every year
    -- Word Cloud generation for top 50 words for every year
- Bigrams:
    -- Bigrams compilations with sorted frequency distribution (top 200) for every year
    -- Function for specific word bigram compilation created for every year. Example result was done for specific word "integration"
    
Bigrams compilation is based on NLTK package, with scoring metrics based on the following methodology:
- Point Mutual Information
- Student T-test
- Chi-Square
- Likelihood Ratio	
