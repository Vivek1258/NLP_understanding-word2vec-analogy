# NLP_understanding-word2vec-analogy
 Word embedding algorithms and models 

 What are Word Embeddings?
 
 In very simplistic terms, Word Embeddings are the texts converted into numbers and there may be different numerical representations of the same text. 
 
 In other words
 A Word Embedding format generally tries to map a word using a dictionary to a vector. Let us break this sentence down into finer details to have a clear view.
 
 
 Take a look at this example – sentence=” Word Embeddings are Word converted into numbers ”

A word in this sentence may be “Embeddings” or “numbers ” etc.

A dictionary may be the list of all unique words in the sentence. So, a dictionary may look like – [‘Word’,’Embeddings’,’are’,’Converted’,’into’,’numbers’]

A vector representation of a word may be a one-hot encoded vector where 1 stands for the position where the word exists and 0 everywhere else. The vector representation of “numbers” in this format according to the above dictionary is [0,0,0,0,0,1] and of converted is[0,0,0,1,0,0].

This is just a very simple method to represent a word in the vector form. Let us look at different types of Word Embeddings or Word Vectors and their advantages and disadvantages over the rest.
 
 
 
 
 NOTE : Here I have taken  any random dataset (corpus) for better results you can go for larger corpus with proper context 
