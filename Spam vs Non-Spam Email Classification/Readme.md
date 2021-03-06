# Spam vs Non Spam Email Detection

Dataset URL: http://archive.ics.uci.edu/ml/datasets/Spambase 

1. *spambase.data* contains the actual data,
2. *spambase.names* and *spambase.DOCUMENTATION* contain the description of the data.

This dataset has 4601 records, each record representing a different email message. Each record is described with 58 attributes (indicated in the aforementioned .names file): attributes 1-57 represent various contentbased characteristics already extracted from each email message (related to the frequency of certain words
or certain punctuation symbols in a message as well as to the usage of capital letters in a message), and the
last attribute represents the class label for each message (spam or non-spam).

## Task
The general task for this assignment is to build two different models for detecting spam messages (based
on the email characteristics that are given): 
1. The best possible model that you can build in terms of the overall predictive accuracy (i.e., not taking any cost information into account)
2. The best cost-sensitive classification model that you can build in terms of the average misclassification cost. 
