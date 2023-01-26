# Operations On Word Vectors
Operations on pre-trained embedding vectors 

## Embedding Vectors Versus One-Hot Vectors
One-hot vectors don't do a good job of capturing the level of similarity between words. This is because every one-hot vector has the same Euclidean distance from any other one-hot vector.

Embedding vectors, such as GloVe vectors, provide much more useful information about the meaning of individual words.  
We can use GloVe vectors to measure the Cosine similarity between two words! 
