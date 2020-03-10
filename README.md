# SMS-Spam-Detection
## Overview
This repository contains the versions of data, figures generated, and Python notebook that comprise an analysis of 5500+ SMS messages in order to develop methods for spam message classification. The Python notebook reads more like a tutorial, where I briefly explain some of the NLP methods used in representing text data numerically specifically using the Bag-of-Words models through tokenizing words and vectorizing messages. This is for my own reference, and yours, as it is difficult to think about large matrices containing TF-IDF values without specifically detailing how the data is transformed. Ultimately, I train and test Naive Bayes and K-Nearest Neighbors models, varying the combinations of features fed into each model in order to see how they affect accuracy scores. I also take a closer look at the nature of misclassification by plotting confusion matrices.

## Data
The data I will be using for this analysis project consists of tagged messages that have been collected for SMS spam research originally by researchers at UC Irvine. The dataset contains 5574 english SMS messages, which I will attempt to classify as spam or not spam by first cleaning, processing, and eventually modeling with various classification methods. This project is mainly for improving my understanding of preprocessing methods for text data (tokens, vectorizers, Bag of Words, TF-IDF, etc.) in addition to some classification techniques commonly used when working with NLP problems (Naive Bayes and KNN).

More detailed information on the dataset including how the dataset was assembled can be found here: https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection.

Reference:

Almeida, T.A., GÃ³mez Hidalgo, J.M., Yamakami, A. Contributions to the Study of SMS Spam Filtering: New Collection and Results. Proceedings of the 2011 ACM Symposium on Document Engineering (DOCENG'11), Mountain View, CA, USA, 2011.

http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/

## How to Run
Make sure you have installed the packages listed in `requirements.txt`. Otherwise, install them by using a command like:
```
pip install -r requirements.txt
```
Download the Python notebook and do what you'd like!
