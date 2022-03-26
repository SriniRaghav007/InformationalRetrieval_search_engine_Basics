# Boolean Query Retrieval!

**Boolean Query Retrieval** is a classical information retrieval (IR) model and, at the same time, the first and most-adopted one. It is used by many IR systems to this day.The BIR is based on [Boolean logic](https://en.wikipedia.org/wiki/Boolean_logic "Boolean logic") and classical [set theory](https://en.wikipedia.org/wiki/Set_theory "Set theory") in that both the documents to be searched and the user's query are conceived as sets of terms (a [bag-of-words model](https://en.wikipedia.org/wiki/Bag-of-words_model "Bag-of-words model")). Retrieval is based on whether or not the documents contain the query terms.


# Dataset used:

Dataset used is **Wikipedia Toxicity**.
Link is: [dataset](https://www.kaggle.com/datasets/manishguptads/wikipedia-toxicity) .

## Method

Here, for processing the corpus, the use of porter-stemmer, tokenization, case handling was applied.
Then the inverted index was obtained.
Finally for processing the request, the use of boolean logic and set theory is applied.
