# Naive-Bayes-Email-Classification

We have a set of emails, half of which were written by one person and the other half by another person at the same company. 

Our objective is to classify the emails as written by one person or the other based only on the text of the email. We will use the Naive Bayes algorithm.

We will start with a list of strings. Each string is the text of an email, which has undergone some basic preprocessing; 
we will then split the dataset into training and testing sets.

One particular feature of Naive Bayes is that it’s a good algorithm for working with text classification. 
When dealing with text, it’s very common to treat each unique word as a feature, and since the typical person’s vocabulary is 
many thousands of words, this makes for a large number of features. The relative simplicity of the algorithm and the 
independent features assumption of Naive Bayes make it a strong performer for classifying texts.
