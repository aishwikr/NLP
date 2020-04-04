### NLP_Basics
Problem Statement


Data: You are given three datasets. Each dataset is in a csv file, where the rows correspond to
documents. Each file has two columns: the first column contains the document id, and the
second column contains the document text.


Task-01: For each of the dataset, your code should be able to do the following:
a. Read the dataset in an appropriate data structure.
b. Tokenize the documents to extract individual terms. Carefully consider the tokenization
decisions.
c. For each document, extract the named entities.
d. For each document, assign POS tags to each token.


Task-02: Once you are able to do the above tasks, generate useful statistics from the dataset
and present them using tables and other visualization techniques. Some of the example
statistics that you can generate are as follows:
a. Frequency statistics of the terms
b. Frequency statistics of the named entities
c. The probability distribution of each of the POS tags


### NLP_using_word2Vec
Data:
1. D: Dataset (first 1000 documents of dataset_1.csv from lab-01)
2. QD : Set of 12 query documents (q_d.csv)
3. QW : Set of 10 query words (w_d.csv)

Task-01: Use TfIdfVectorizer to get representations of documents from D. Show some
examples to show the individual vectors. Compare your python results with manually computed
results (can use grep function for word frequency count).
Task-02: For each of the query documents from QD, find the closest documents according to
the documents vector representations.
Task-03: Learn word2vec model from data D.
Task-04: For each query word from QW, we have to find the closest words according to the
word vector representations. You can make use of the gensim functions for finding the most
similar words.
Additional Tasks:
Task-05: Represent a document as the average of the vectors for the words that it contains. For
each of the query documents from QD, find the closest documents according to the documents
vector representations.
Task-06: Represent a document as the weighted-average of the vectors for the words that it
contains. The weight should be the idf of the word. For each of the query documents from QD,
find the closest documents according to the documents vector representations.
