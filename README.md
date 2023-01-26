# Operations On Word Vectors
Operations on pre-trained embedding vectors 

## Embedding Vectors Versus One-Hot Vectors
One-hot vectors don't do a good job of capturing the level of similarity between words. This is because every one-hot vector has the same Euclidean distance from any other one-hot vector.

Embedding vectors, such as GloVe vectors, provide much more useful information about the meaning of individual words.  
We can use GloVe vectors to measure the Cosine similarity between two words!

Here we are using Glove Vectors from `glove.6B.50d.txt` which can be downloaded from internet.

## Word Analogy Task

This projects aims to complete Word Analogy such as:

* <font color='brown'>"*a* is to *b* as *c* is to **____**"</font>. 

* An example is:  
    <font color='brown'> '*man* is to *woman* as *king* is to *queen*' </font>. 
