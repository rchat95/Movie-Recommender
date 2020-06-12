# Movie-Recommender
A movie recommendation system built on the GroupLens dataset.

Dataset used - "ml-latest-small" dataset from the GroupLens' MovieLens website (https://grouplens.org/datasets/movielens/)

The notebook contains two approaches to predict the top 10 movie recommendations, one is a correlation based approach wherein I have analyzed the results of three correlation metrics - Pearson, Kendall and Spearman.

In the second approach, I have built a nearest neighbors algorithm from scratch with some hand built distance metrics such as cosine similarity, euclidean distance, manhattan distance and normalized euclidean distance.

It is seen that out of all the distance measures, cosine similarity gave the best results.

A detailed report can be found at the attached PDF file, titled "ML Project Report.pdf".
