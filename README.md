# Sentiment-Analysis-of-Data-Pulled-from-Twitter
- Author: Adegbenro Michael Olusola:
  - Please, leave a comment if you find my work useful

This work allows you to extract your own data from Twitter and Save on your local drive. You need API key to do this. 
Note: From the machine learning point of view, raw text is useless. Only if we manage to transform it into meaningful numbers, can we feed it into our machine-learning algorithms such as clustering. The same is true for more mundane operations on text, such as similarity measurement

This project can pull data from Tweeter but to do that you need to request for your own API keys specified below (I removed mine):

my_api_key = "xxxxxxxxx"
my_api_secret = "yyyyyyy"
If you don't have API keys already, you may use "Raw Data" which i pulled from tweeter using:

search_query = "#Buhari -filter:retweet"
(Buahri is the perseident of Nigeria from 2015 to 2023)
You can specifiy amount of tweets you want to pull. Here I pulled 100

This work covers:
- Data extraction from Twitter 
- If you dont have API key from Twiiter, kinldy use the attached data "Raw Data"
- Clean data
- Lemmatization and Steamming
- Removing Stop-words
- Vader Sentiment Analysis
- WordCloud using atual clean data
- Polarity and Subjectivity
- Check Analysis Accuracy and error
