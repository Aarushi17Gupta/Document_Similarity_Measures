## Document Similarity Measures
#### Text similarity is used to discover the most similar texts. It is used to discover similar documents using various measures such as Jaccard and Cosine similarity

#### Document similarity can be used in any search engines such as Google. Text similarity can also be used in document recommendations. 

#### Document similarity is calculated by taking document distance. Document distance is the concept where words or documents are treated as vectors and various similarity measures are calculated. 


There are many ways of matching the similarity between texts

### 1. FuzzyWuzzy 
FuzzyWuzzy is a library of Python which is used for string matching.One of the easiest ways of comparing text in python is using the fuzzy-wuzzy library. Here, we get a score out of 100, based on the similarity of the strings. Basically, we are given the similarity index. The library uses Levenshtein distance to calculate the difference between two strings.

### 2. Cosine similarity 
Cosine similarity measures the cosine of the angle between two vectors. Here vectors can be bag of words, TF-IDF, or Doc2Vec. Cosine similarity is best suitable for where repeated words are more important and can work on any size of the document. Its value ranges from 0 to 90 degrees, where 0 degree means the two documents are exactly identical and 90 degree means that the two documents are very  different. 

###### TF-IDF Vectorizer- Term frequency-inverse document frequency (TF-IDF) vectorization is a simple and convenient way to characterize bodies of text. Due to its simplicity, this method scales better than some other topic modeling techniques when dealing with large datasets.
Term frequency refers to how often a term (or token) occurs within a given document. Since the documents are quite small, we don't observe a term that appears more than once.

### 3. Jaccard Similarity
Jaccard Similarity is the ratio of common words to total unique words or we can say the intersection of words to the union of words in both the documents.Its scores ranges between 0-1. 1 represents the higher similarity while 0 represents the no similarity. It considers only the unique set of words for each sentence and does not give importance to the duplication of words.

###### These measures are not all the same thing and they yield quite different results. Yet they are all types of distances, ways of describing the relationship between two data samples.
