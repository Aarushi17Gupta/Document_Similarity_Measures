## Document Similarity Measures
#### Text similarity is used to discover the most similar texts. It is used to discover similar documents using various measures such as Jaccard and Cosine similarity
#### Document similarity can be used in any search engines such as Google. Text similarity can also be used in document recommendations. 
There are many ways of matching the similarity between texts
### 1. FuzzyWuzzy 
FuzzyWuzzy is a library of Python which is used for string matching.One of the easiest ways of comparing text in python is using the fuzzy-wuzzy library. Here, we get a score out of 100, based on the similarity of the strings. Basically, we are given the similarity index. The library uses Levenshtein distance to calculate the difference between two strings.
### 2. Cosine similarity 
Cosine similarity measures the cosine of the angle between two vectors. Here vectors can be bag of words, TF-IDF, or Doc2Vec. Cosine similarity is best suitable for where repeated words are more important and can work on any size of the document.
### 3. Jaccard Similarity
Jaccard Similarity is the ratio of common words to total unique words or we can say the intersection of words to the union of words in both the documents.Its scores ranges between 0-1. 1 represents the higher similarity while 0 represents the no similarity. It considers only the unique set of words for each sentence and does not give importance to the duplication of words.

