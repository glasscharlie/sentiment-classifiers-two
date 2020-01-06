# sentiment-classifiers-two

Author: Charles Glass Version: 1.0.0

Overview
Identify a dataset suitable for sentiment classification - reviews with an even distribution are a good option. Access it either externally or from within your repository as appropriate. Determine an appropriate spread for your sentiments and add a column associating them with the appropriate reviews. Identify and normalize any issues in your dataset. Do the preprocessing work utilizing Keras and Tensorflow taking a One-Hot Vector approach.

Data Set
I chose a amazon headphones review dataset, the important categories for this dataset are the review bodies and the number of stars that the person gave the headphones. The was I see people as reviewing, 1 or 2 stars is a pretty negative review, 3 stars is pretty neutral, and 4 or 5 stars is a pretty positive review.I used tokenizer to get my data set into sequences, and then used tokenizer to get my data set into a matrix.

Architecture
This application is used Python, pandas, jupyterlab, karas, numpy and tensorflow

Change Log
12-30-2019 3:30pm - Cleaned the data set and did the processing work -->
1-4-2020 4:00pm - created a model, trained classifier, and saved the trained model