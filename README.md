# Twitter-Sentiment-Analysis

It is used to understand how the public feels about something at a particular moment in time and also track
 how those opinion change over time

Essential may analyze sentiment about:

 1) Product
 2) Service
 3) Competitors
 4) Reputation
 
# Prerequisites

 1) Hadoop
 2) Hive
 3) Flume
 4) Java
 5) StopWord
 6) Affinn Dictionary
 7) Twitter App 

# Steps For Sentiment Analysis

 1) Load Data to Hive tables 
 2) Filteration – remove URL links (e.g. http://example.com), Twitter user names (e.g. @alex – with symbol @ indicating a user name),
 3) Tokenization –  Segment text by splitting it by spaces and punctuation marks, and form a bag of words.
 4) Removing stop words – we remove articles (“a”, “an”, “the”) from the bag of words.
 5) Comparing with Sentiword/Afinn Dictionary –we compare the articles with Dictionary to predict that the word is negative,positive or neutral.

# TODO
 
 1) Add Visualization Tools.
 2) Make a Gui Version.
 3) Apply Machine Learning Techniques.


Look into the Readme folder to learn more about How to load and Analyse.
