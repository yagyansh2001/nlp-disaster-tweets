# nlp-disaster-tweets
Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster.

### Objective- To build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. 

Each sample in the train and test set has the following information:

1.The text of a tweet

2.A keyword from that tweet (although this may be blank!)

3.The location the tweet was sent from (may also be blank)

Columns

id - a unique identifier for each tweet

text - the text of the tweet

location - the location the tweet was sent from (may be blank)

keyword - a particular keyword from the tweet (may be blank)

target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)
