# Predicting-next-words-using-NLP
An RNN model built on predicting next words in a Shakespearean dataset using Bidirectional LSTM in NLP
### During the phase of this project, the following operations were been carried out:
+ Data collection from https://drive.google.com/uc?id=108jAePKK4R3BVYBbYJZ32JWUwxeMg20K
+ Reading in the datasets
+ Tokenizing and vectorizing the texts in the dataset using the Tokenizer class in TensorFlow.
+ Conversion of the texts into sequences
+ Adding padding to the sequences to ensure uniformity in length of the sequences
+ Splitting the padded sequences into the features and the labels set and performing one hot encoding on the label sets
+ Building of the model using Bidirectional LSTM
+ Visualization plot showing a curve depicting the relationship between training time (epochs) and it's effects on the accuracy score and accuracy loss.
+ Testing and saving of the model
