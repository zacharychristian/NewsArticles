# NewsArticles

In this project, I will create models that classify news articles based on word counts. The models I will be using are Naive Bayes, K Nearest Neighbor, and KMeans. I will also be applying some techniques like dimensionality reduction and automated hyperparameter decisions.

In order to use text as data, I will need to use a vectorizer. In this project, I use TFIDFVectorizer. The way a vectorizer works is it first takes in the word counts of a document and turns each word into a vector. TFIDF stands for term frequency inverse document frquency. This means that words that don't appear as often have a higher weight to them. This means that words that are specific to a certain category have a higher weight to them, making it easier to categorize them correctly. All of the vectors in a document are put together into a matrix. Accuracies of models are calculated using cosine similarity.

Dimensionality reduction is used in this project to reduce time and size costs.

I will use pipelines in this project quite a bit because I believe it reflects a real life project more. Pipelines provide more reuseability and can be easier to see what is happening under the hood.
