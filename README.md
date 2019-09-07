## TEXT ANALYTICS USING NLP (Natural Language Processing)
Web scrapping - Twitter data

#### SUMMARY:
Stan Lee, one of America's most prolific comic book writers, died in Los Angeles at the age of ninety-five on November 12, 2018. Here, I aim to analyze social media's response, particularly Twitter, to his death. 

#### PROJECT GOALS:
* Explore tweets to reveal interesting insights about user activity after his death.
* Build a machine learning model that is capable of accurately classifyig the sentiment of a tweet as either positive, neutral or negative.

#### PACKAGES USED:
* Scikit-Learn, Numpy, Pandas, NLTK, Textblob, Matplotlib, and Tweepy among others.

#### MOTIVATION:
Stan Lee was an American comic book writer, editor, publisher, and producer. He rose through the ranks of a family-run business to become Marvel Comics' primary creative leader for two decades, leading its expansion from a small division of a publishing house to a multimedia corporation that dominated the comics industry. Lee was inducted into the comic book industry's Will Eisner Award Hall of Fame in 1994 and the Jack Kirby Hall of Fame in 1995. He received the NEA's National Medal of Arts in 2008.

As a fan of Marvel comics myself, I wanted to explore his life and work in greater detail using machine learning!

#### DATA COLLECTION:
Data for the analysis was collected through Twitter's public APIs. *([How to extract tweets using Twitter's public APIs](https://medium.com/@jayeshsrivastava470/how-to-extract-tweets-from-twitter-in-python-47dd07f4e8e7))*

* I used the following keywords to filter the extraction - Stan Lee, StanLee, Stanley Martin Lieber

*PS: Adil Moujahid does a great job [introducing Text Mining using Twitter's streaming API and Python](http://adilmoujahid.com/posts/2014/07/twitter-analytics/)*

### DESCRIPTIVE ANALYTICS (EDA)

#### Top 5 Languages used to tweet:

![Top_5_lang](https://user-images.githubusercontent.com/54816432/64467703-1af91680-d0e9-11e9-8ab9-bc31ab73e0af.png)

*English comes in at #1 followed by Spanish*

#### Time Series analysis displaying number of likes vs date of creation (of tweets):

![#of_likes_vs_date](https://user-images.githubusercontent.com/54816432/64467754-c30edf80-d0e9-11e9-9aef-bb10f382d24f.png)

*Tweet with the most likes was created on the 24th of November, 2018*

#### Tweet with the most number of likes:

![most_liked_tweet](https://user-images.githubusercontent.com/54816432/64467823-bd65c980-d0ea-11e9-9d67-d1e93b91ca30.png)

### SENTIMENT ANALYSIS

#### Wordcloud:

![wordcloud](https://user-images.githubusercontent.com/54816432/64468598-a3c97f80-d0f4-11e9-8a7e-2c221b56cb91.png)

Important words include:
1. angeles
2. awesome
3. respect
4. memorial

#### Percent(%) distribution of sentiments:

![sentiment_distribution](https://user-images.githubusercontent.com/54816432/64468717-eb9cd680-d0f5-11e9-8f86-835a89db4762.png)

*Majority of the tweets were of a positive sentiment*

### FOLDER CONTENTS:

Text analytics using NLP - The life of Stan Lee.ipynb: Contains coded steps undertaken to 
1. Extract the relevant tweets
2. Pre-process and structure the data for analysis
3. Carry out some descriptive analytics
4. Perform sentiment analysis and build a model for sentiment classification

NLP_Life_of_Stan_Lee.pptx: Contains the above results and more in PPT format for an audience.

### Please feel free to use any of the steps shown above and have fun coding!! 
