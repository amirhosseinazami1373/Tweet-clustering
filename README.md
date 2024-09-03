<h1 style="display: flex; justify-content: space-between; align-items: right;">
    <span>Tweet-clustering</span>
    <img src="https://gist.githubusercontent.com/mindplay-dk/56a9e2ada89b1fc8c7834c8c18b37904/raw/563036ceb5ee8a31b7a828c33b11ba7088340e29/twitter.svg" style="width: 100px;"/>
</h1>

Cluster tweets using the Jaccard Distance metric and the K-means clustering algorithm. This approach groups similar tweets together, which is useful for applications like trend analysis and content organization on Twitter.

The data is accessible through the link below: 

https://archive.ics.uci.edu/dataset/438/health+news+in+twitter

Steps:

**Tokenize Tweets**: Convert tweets into sets of words.

**Define Jaccard Distance**: Calculate the similarity between sets.

**Initialize Centroids**: Randomly pick k tweets as initial centroids.

**Cluster Assignment**: Assign each tweet to the nearest centroid based on Jaccard distance.

**Update Centroids**: Update each centroid to the tweet in the cluster that minimizes the sum of distances to other tweets in the same cluster.

**Calculate SSE**: Sum of Squared Errors for evaluation.
