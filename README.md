# word2vec-and-GloVe-embeddings-for-fake-news-text-classification
Natural Language Processing: An analysis and comparison of word2vec and GloVe embeddings for fake news text classification

In this project we explore global vectors for word representation (GloVe vectors), and discuss what needs they were created to solve, how they are constructed and how the method compares to word2vec. As part of the comparison, we explore the differences in the types of similar words the two methods produce and briefly discuss the mathematical reasoning behind that.  We also train two LSTM classification models to identify fake news with both a word2vec and a GloVe embedding layer – which perform identically. 

Word2vec and Glove are built using different methodologies which is clear when examining the words these vectors generate when given a target word, however, these differences were not found to  effect performance of a binary classification task using and LSTM neural model. 
