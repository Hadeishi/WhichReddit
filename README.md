# WhichReddit? NLP Analysis Towards Unifying Specialists

### Description

Problem: Specialists of different scientific stripes use wildly different sets of terminology in their daily communication. Yet, there is an increasing need for specialists to be able to communicate with one another. Can we use NLP to identify these terms and begin bridging the gap between specialities? In this project, we will first build a model that will detemine whether a particular post came from one of two subreddits.

Solution: Collect data from two distinct subreddits (datascience and genetics). Use Natural Language Processing to analyze words from these subreddits, comparing 5 different models to distinguish between subreddits (models included logistic regression, K-Nearest Neighbors, decision trees, random forests, and adaboost).

Dataset: 1866 posts scraped in early June, 2018 from datascience and genetics subreddits.

Conclusion: All 5 models overfit to the data used to train our models. Comparing accuracy at predicting which subreddit testing data that had not been used to created our model, logistic regression was the most accurate (93.6% accuracy).

Future Directions:  Optimize models by GridSearching and tuning hyperparameters.  Supplement text analysis by factoring in other data, such as number of comments made, or length of posts.  Try analyzing just the titles of posts and see whether models can be used to predict on a more limited dataset. Use PCA to identify components defining word vector space to identify important words separating specialists.
