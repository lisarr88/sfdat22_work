#7:
I notice that 2 clusters is optimal, and only one record falls into cluster 1.
Ideally there should be more records in each cluster, so it's possible that the clustering isn't working well
because there are too many columns in the dataset.
We can't really draw any conclusions with just a few records separated from the rest.


#15:
From the KNN analysis, Trump is the easiest candidate to predict. That makes sense because he is the only Republican candidate.
Bernie was the most difficult candidate to predict. That's probably because he shares the same party preference as Hillary.
He also may have supporters who are more outside of traditional party beliefs, like Trump.

From the logistic regression analysis, democrat was easier to predict.
That's probably because there were more democrat records than Republican.
Maybe that is because Trump is a more moderate Republican.


#16:
I can add an indicator variable for whether or not there is an @ symbol present in the tweet.
That would tell me whether or not the person who tweeted is tagging someone else in their tweet.
It's possible that one candidate's followers tag people in their tweets more often.

I can also add an indicator variable for whether or not there is a '//' present in the tweet.
That would tell me whether or not the person who tweeted included a website in their tweet.
It's possible that one candidate's followers may include websites more often than others.