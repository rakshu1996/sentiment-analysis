# sentiment-analysis
Sentiment analysis refers to the field of study where we make analysis on people’s opinion, their feedback, and response. It plays a big role in improving business productivity especially where customers are distributed globally. In this research we collected a movie review data from twitter, cleaned that data, analysed the response of people about that movie and hence made conclusion on the basis of their response. We can also extend this research for future prediction, prediction of stock price, political elections, improve customer service, analyse market strategy etc.
There aremany platforms to collect the movie reviews. We have used twitter API to collect the data. 
then we have performed tokenization with the methods sentence and words.
The sentiment property returns a named tuple of the form Sentiment (polarity, subjectivity). The polarity score is a float within the range [-1.0, 1.0]. The subjectivity is a float within the range [0.0, 1.0] where 0.0 is very objective and 1.0 is very subjective.
We can iterate the publice_tweets array, and check the sentiment of the text of each tweet based on the polarity.
We can see that the sentiment of the tweet is displayed.
