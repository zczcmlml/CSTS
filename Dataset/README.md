// Build by Xiaoke Huang

There are two data set. One is used for storing all the detail information of each article. Such as keywords. Title, headline. And other one is the clusters array.

The articles attribute in the clustersArray object is sorted by pagerank.
I designed it for all the possible usage. It should be fine for you to do everything.

The article_range shows the first article index and last articles index in this time stamp.

This file can be used to detect which articles are new coming articles, and which articles are old left articles.

The meaning of parent:
the share number to previous clustering result.
for example, for a cluster parent is [10, 1, 0, 0, 0]
this means, this cluster has 10 same articles with the 0 cluster in previous time stamp.
And has 1 same article with the 1 cluster in previous time stamp.
And does not have any same ariticles for the rest of other clusters.