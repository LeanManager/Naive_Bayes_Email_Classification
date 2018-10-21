# Naive-Bayes-Email-Classification

We have a set of emails, half of which were written by one person and the other half by another person at the same company. 

Our objective is to classify the emails as written by one person or the other based only on the text of the email. We will use the Naive Bayes algorithm. We will also print out the accuracy of our model.

We will start with a list of strings. Each string is the text of an email, which has undergone some basic preprocessing; 
we will then split the dataset into training and testing sets.

One particular feature of Naive Bayes is that it’s a good algorithm for working with text classification. 
When dealing with text, it’s very common to treat each unique word as a feature, and since the typical person’s vocabulary is 
many thousands of words, this makes for a large number of features. The relative simplicity of the algorithm and the 
independent features assumption of Naive Bayes make it a strong performer for classifying texts.

We will need to install:
1) Python 3 and pip3
2) Scikit-learn
3) Natural language toolkit
4) Numpy
5) Scipy

Clone this repository into a directory of your choice, then run the startup.py script from there using Terminal (MacOS) with the command 'python startup.py'.
It will first check for the Python modules, then download and unzip a large dataset that we will use. The download/unzipping can take a while.

Next, run the nb_author_id.py script with the command 'python nb_author_id.py' and observe the output.
