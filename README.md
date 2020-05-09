# Multi-Class-Text-Classification-Wines-NLP
Multiclass text classification using two models : Keras Custom Embeddings and Google BERT

Change the file_paths according to your directory.
Code can be un directly in google colab.


Two models have been tested:
1. Using Keras' Custom Embedding Layer:
The model was trained from scratch for word embeddings; further propogated to RNN architecture resulting in 
77% train accuracy and 67% validation accuracy.

2. Using Tansfer Learning with Google BERT weights:
The model was trained using pre-trained Google BERT word embeddings giving better results with
83% train accuracy and 74% validation accuracy.
