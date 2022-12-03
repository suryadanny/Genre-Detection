# Genre-Detection

The goal of the project is to predict and label a movie plot summary with its appropriate genre label. project is based on Recurrent Neural Networks using LSTM units for labelling.

**DateSet -** 

The dataset can be downloaded from - ftp://ftp.fu-berlin.de/pub/misc/movies/database/frozendata/ , one would need to parse the file inorder to properly attribute dataset with titles, plot and genres. The parsing activity is already done and the respective csv file attached in the repository.

made use of Flask to provide a basic web application interface as a wrapper for the RNN model.

**Libraries used -**

Keras 2.0
Flask - Micro webframework for python

**Results -**

The model has been able to achieve an accuracy of 74% on validation dataset
Acheived an F1 score of 0.91 on validation set

**Usage -**

Run the program using - $ python start.py

Use endpoint: http://localhost/node/7777

