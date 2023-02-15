# Text Classification
This assignment uses BBC Dataset which is available for download with this assignment. 
Prepare both train and test data available in respective folders, each folder represents a class label. (business, entertainment, politics, sport, tech).  By 'prepare', I mean remove stop words, punctuation, numbers and tokenize both the folders to create sequences. 
Once sequences are created for both test and train, 

1.	create a Sequential model with an embedding layer with maximum words set to 10000 and embedding dim to 64. 
2.	add two dense layers with 32 and 16 with appropriate activation functions for these hidden layers and also for output layer
3.	train the model while sparing 20% for validation during each epochs of total 10 epochs
4.	test model performance on test data and report test accuracy
5.	use pretrained GloVe in above model with 100 dim and report test accuracy
6.	use FastText in above model and report test accuracy
7.	use Word2Vec in above model and report test accuracy
8.	for each of the 5, 6, 7, please replace dense hidden layers with LSTM layers and report the test accuracy
9.	Finally, inside a text cell of CoLab create a summary table that reports all these accuracies and your comments as to which model performs best on this dataset

