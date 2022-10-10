# Genre-Detection

The goal of the project is to predict and label a movie plot summary with its appropriate genre label. project is based on Recurrent Neural Networks using LSTM units for labelling.

DateSet - 

The dataset can be downloaded from - ftp://ftp.fu-berlin.de/pub/misc/movies/database/frozendata/ , one would need to parse the file inorder to properly attribute dataset with titles, plot and genres. The parsing activity is already done and the respective csv file attached in the repository.

made use of Flask to provide a basic web application interface as a wrapper for the RNN model.

Acheived a accuracy of 71% on the test set for the parsed dataset


Run the program using - $ python start.py

Use endpoint: http://localhost/node/7777

