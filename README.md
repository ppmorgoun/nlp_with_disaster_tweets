# NLP Tweet Classifier: Distinguishing tweets about disasters from tweets with disastrous language
Kaggle competition: https://www.kaggle.com/c/nlp-getting-started/overview
Best accuracy on test set: 78.6%, with a Random Forrest classifier.

I used various naive ML approaches to see which technqiue yielded the best results. 

Preprocessing my data:
    1). Remove all non alphanumeric characters excluding the hashtag #
    2). Removes common english stopwords
    3). Set all characters to lowercase
    4). OPTIONAL: destem each word in each tweet
    5). OPTIONAL: delemmatize each word in each tweet
