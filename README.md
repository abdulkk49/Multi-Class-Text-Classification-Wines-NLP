# Multi-Class-Text-Classification-Wines-NLP
Multiclass text classification using two models : Keras Custom Embeddings and Google BERT

Change the file paths according to your directory.
Code can be run directly in google colab.

###### The file test_var.csv stores the final predicted results.
###### The files country_extract.csv and vintage_extract.csv give some insights and data distributions. 
###### The images also reflect some information ragarding wines.

Two models have been tested:
#### 1. Using Keras' Custom Embedding Layer:
The model was trained from scratch for word embeddings; further propogated to RNN architecture resulting in 
77% train accuracy and 67% validation accuracy.

#### 2. Using Tansfer Learning with Google BERT weights:
The model was trained using pre-trained Google BERT word embeddings giving better results with
83% train accuracy and 74% validation accuracy.

Results can probably be futher improved by removing stopwords and then feeding it to Google BERT architecture.
