# Coffee shops reviews sentiment analysis with python

Imagine you are moving to a new city where you have never been before, and additionally you are crazy foodies. Obviously, you want to discover the best coffee shops in your brand new neighbourhood (or you are considering between some districts and want to compare them). As you now, mouth publicity is the most efficient way of marketing promotion so fist thing that you are doing is reading some google reviews. But it is almost impossible to manually evaluate each comment.

What you can do is build model that will classify customers' attitude towards service and food based on given reviews.

Customer satisfaction is vital for every business, and such model can be used to enhance business opportunities and improve customers experiences.

The purpose of this project is to build the NLP model, that will we able to decide whether the attender had positive, neutral or negative impression after visiting coffee shops.

The data is scrapped from google place reviews and consists of 1165 reviews of Surry Hills coffee shops (20) in Sydney, Australia.


This project has several steps:
1. Data exploration
2. Data preprocessing
  * removing punctutiations and stop words
  * data stemming and lemmatization
  * vectorization with Count Vectorizer and TF-IDF
3. Data visualization (frequency distribution and word cloud)
4. Modeling
  * Multinomial Naive Bayes
  * Logistic Regression
  * Xgboost Classification
5. Testing
6. Attempt to improve the outcome with n-grams

Reviews with score 1.0 and 2.0 will be assigned to negative sentiment, 3.0 and 4.0 will indicate neutral attitude and 5.0 will respond for positive sentiment.



