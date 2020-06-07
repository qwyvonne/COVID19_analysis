# COVID19_analysis
**Project Goal**: utilizing social media to identify needs for emergency response at the local or community level

**Final Product**: a dataset that contains tweet_id, tweet_content, post_time, and Relevancy_Prediction (relevant or irrelevant)

**Data Source**: Twitter, a manually labeled dataset (labeled as relevant or irrelevant) 

**Package and library**: GetOldTweets3, NumPy, Pandas, nltk

**Data Collection**
Twitter: tweets that focus on prevention and risk of COVID-19 from Twitter using GetOldTweets3
Manually Labeled Dataset: provided a set of 511 tweets from the NCR that he had manually labeled as relevant (86) or irrelevant (425) depending on whether they pertained to prevention and/or risk. 

**Data Cleansing**
Worked with NLTK library to transform data (lemmatizing word, removing white space, hyperlink, Latin characters and digits)

**Data Splitting** 
The labeled tweets were randomly divided by SWB into training and test sets with an 80:20 split. (A small number of tweet ids had been deleted and were no longer accessible for modeling, leaving 76 relevant and 387 irrelevant tweets.)

**Model Building**
SVM 
Logistics Regression 
Naive Bayes

**Performance Measurement**
Specificity, Sensitivity, PPV, NPV

**Conclusions**
These models necessarily reflect the judgment that went into the labeling. Moving forward, this could be improved by a larger set of data labeled by a group of experts who have reached consensus on the essential distinctions between relevant and irrelevant tweets.
