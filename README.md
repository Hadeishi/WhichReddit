# WhichReddit: Web APIs & Classification

### Description

Problem:  Detemine whether a particular post came from one of two subreddits.

Solution:  Collect data from two distinct subreddits (datascience and genetics). Use Natural Language Processing to analyze words from these subreddits, comparing 5 different base models to distinguish between subreddits (logistic regression, K-Nearest Neighbors, decision trees, random forests, and adaboost).

Conclusion:  All 5 models overfit to the data used to train our models. Comparing accuracy at predicting which subreddit testing data that had not been used to created our model, logistic regression was the most accurate (93.6% accuracy).

Future Directions:  Optimize models by tuning hyperparameters.  Supplement text analysis by factoring in other data, such as number of comments made, or length of posts.  Try analyzing just the titles of posts and see whether models can be used to predict on a more limited dataset.