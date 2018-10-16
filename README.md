Classify your Subreddit Post by Machine Learning!

There are hundreds and thousands of posts per day on reddit.com and we definitely want computers to be able to “recognize” each post by its subreddit category for multiple usages!
But how?

Machine learning algorithms can easily help! In this project, we showcase how this is done by machine learning. Two popular kinds of subreddit posts are scrapped from reddit.com: Boardgames and True reddits. NLP is used next to analyze the word frequency for each post and a model is built on top of that to predict which category the post belongs to. The parameters are fine tuned later to optimize results. 96 of 100 posts can be categorized correctly.

This project used logistic regression and random forest classifier for classification model and both gave very high accuracy scores of 95% ~ 96%. Logistic regression is sightly better and the difference is minor that they are essentially equivalent in terms of accuracy. The optimization using gridserachCV is very useful and compationaly expensive so a minimum optimization was carried out and good convergence on train and test scores achieved. The precision, recall and f1-score listed as a reference but accuracy is our target metrics cause we don't care to optimize either false negatives or false positives in this particular case.

I believe there are more we can work to expand the results to a more diverse and in depth application. 
