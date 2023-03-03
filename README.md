# Pet_Food_Sentiment_Analysis

The main goal is to conduct sentiment analysis on the pet food company tweets. In part, the question is to see what else influences the sentiment analysis to become more or less positive.

The pet food companies are:

Purina: https://www.purina.com/
Diamond Pet: https://www.diamondpet.com/
Wellness Pet Food: https://www.wellnesspetfood.com/
Blue Buffalo: https://bluebuffalo.com/

Preparing the text data for sentiment analysis is part of the modeling effort. The sentiment score for each tweet was cast in a binary fashion from spaCy's sentiment analysis.

Most of the initial code for connecting to the Twitter API was modified from Samantha Jone's article on Tweepy: https://www.linkedin.com/pulse/extracting-tweet-information-tweepy-beautifulsoup-samantha-jones/### 

The Tweepy site is self is here: https://www.tweepy.org/https://www.tweepy.org/

In the EDA, there are a few differences between the companies. For example, Purina has a different set of top adjectives and almost always maxes out the tweet length. From these features, the goal was to focus on features that might correlate with increased positive sentiment and explore linguistic qualities with NLP for rhetorical outreach.

In the last notebook, attempts were made to find a successful enough ML model to test out predictive positive sentiment apart from words themselves.

Features in final model were sparse, and most of the engineered features worsened several models' predictive powers.

Target variable: sentiment_cut (1 or 0 based on rounding of Positive sentiment score)
UserName
Mention_Count
Count_ADJs
Count_NOUNS 
Count_VERBS  
