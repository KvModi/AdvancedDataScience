# AdvancedDataScience 

Music Mood Classifier 

Aim: Build a machine learning model to classify Chinese songs in between happy or sad. 

Step 1: File: https://bit.ly/2IdPsuZ
Preparing the data:
    For the purpose of this exercise, we will build models using these datasets:
    • https://raw.githubusercontent.com/rasbt/musicmood/master/dataset/training/train_lyrics_1000.csv
    • https://github.com/rasbt/musicmood/blob/master/dataset/validation/valid_lyrics_200.csv


We divided the above dataset into test and train, vectorizing the data, removed the stops words.
used to-idf to rank the words and classify them into happy or sad words.

The accuracy of the model:

Accuracy for train is:  99.7
Precision for train  is:  99.33184855233853
Recall for train is:  100.0
F1 score for train is:  99.66480446927373

Accuracy for the test is:  70.0
Precision for the test is:  75.28089887640449
Recall for the test is:  63.8095238095238
F1 score for the test is:  69.0721649484536

The function model_predict is used to make the prediction.
 
