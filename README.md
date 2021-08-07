# Electric Vehicle Sentiment Trading

This Project was done using Natural Language Processing (NLP) Techniques . Python libraries like Pandas (for Data Cleaning/Manipulation), Tweepy (for Tweets Mining), NLTK (Natural Language Toolkit), TextBlob (for Sentiment Analysis), MatPlotlib & WordCloud (for Data Exploration), Emot (for Emojis identification), Plotly (for some Data Visualisation) were used for this project.


In the Jupyter Notebook, we carried out the following steps for the project:

Import Libraries
Tweets Mining
Data Cleaning
Tweets Processing
Sentiment Analysis
Classification 
RandomForestRegressor


To reach the ultimate goal, there was a need to clean up the individual tweets. To make this easy, we created a function "preProcessTweets" in my Python program which we further applied to the "Tweets" to produce the desired results. This user-defined function was used to remove punctuations, links, emojis, and stop words from the tweets in a single run. Additionally, we used a concept known as "Tokenization" in NLP. It is a method of splitting a sentence into smaller units called "tokens" to remove unnecessary elements. Another technique worthy of mention is "Lemmatization". This is a process of returning words to their "base" form. 


To get the most common words used to describe "Electric Vehicle", we used the POS-tag (Parts of Speech tagging) module in the NLTK library. Using the WordCloud library, one can generate a Word Cloud based on word frequency and superimpose these words on any image. We used the Twitter logo and Matplotlib to display the image. The Word Cloud shows the words with higher frequency in bigger text size while the "not-so" common words are in smaller text sizes.

![alt text](wordcloud.png)

For this analysis, we used Vedar and TextBlob. Text Blob analyzes sentences by giving each tweet a Subjectivity and Polarity score.  Based on the Polarity scores, one can define which tweets were Positive, Negative, or Neutral. A Polarity score of < 0 is Negative, 0 is Neutral while > 0 is Positive. 

![alt text](plot_circle.png)

Some of the insights we generated are stated below:

Tweet Sentiments: we were not surprised by the proportion of the sentiment categories because, for most people, the prime electric vehicle company to talk about was TESLA. However, we found minimum level of mixed attitude towards the electric vehicle, hence, 12.5% of the tweets being Negative. 