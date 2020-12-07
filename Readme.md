# Statistical Models

Feature engineering techniques:

- Bag of Words Model (TF)
- Bag of N-grams Model
- TF-IDF Model

There are some potential problems which might arise with the Bag of Words model when it is used on large corpora. Since the feature vectors are based on absolute term frequencies, there might be some terms which occur frequently across all documents and these may tend to overshadow other terms in the feature set. The TF-IDF model tries to combat this issue by using a scaling or normalizing factor in its computation. ___TF-IDF___ stands for __Term Frequency-Inverse Document Frequency__, which uses a combination of two metrics in its computation, namely: ___term frequency (tf)___ and ___inverse document frequency (idf)___. This technique was developed for ranking results for queries in search engines and now it is an indispensable model in the world of information retrieval and NLP.

Mathematically, we can define TF-IDF as ___tfidf = tf x idf___, which can be expanded further to be represented as follows.

Here, ___tfidf(w, D)___ is the TF-IDF score for word __w__ in document __D__. 
- The term ___tf(w, D)___ represents the term frequency of the word __w__ in document __D__, which can be obtained from the Bag of Words model. 
- The term ___idf(w, D)___ is the inverse document frequency for the term __w__, which can be computed as the log transform of the total number of documents in the corpus __C__ divided by the document frequency of the word __w__, which is basically the frequency of documents in the corpus where the word __w__ occurs. 
- Similarity Features
- Clustering using Document Similarity Features


# Deep Learning Models

- Word2Vec
- GloVe
- FastText

# Transfer Learning

- Google Word2vec
- BERT ( Similarity & Representantion)

- Word2Vec
- GloVe
- FastText


