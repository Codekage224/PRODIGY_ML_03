# A SVM Model to classify DOGS AND CATS

Welcome people!!!.  
<br>
This is a SVM model which classifies Cats and Dogs.  
<br>
The data set i used is obtained from kaggle . [__link__](https://www.kaggle.com/datasets/karakaggle/kaggle-cat-vs-dog-dataset "Cats and Dogs images").  
<br>
The Dataset has almost 12000 images to train on for both cats and dogs.  
<br>
To Use the Data set, Use the Kaggle API Token (A JSON FILE NAMED="kaggle.json"),by uploading it in google colab.(I Ran this file in google colab)
<br>
### Steps involved are:-
1) Extracting the data from the downloaded zip file
2) Resize all the images to a suitable dimension (50 X 50- in mycase)
3) Shuffle the data for a round exposure of both Dogs and cats.
4) Split the data into both Train and Test data.
5) Fit the model with Train Data and train it.
6) now Fit the model with Test Data and See the results.
