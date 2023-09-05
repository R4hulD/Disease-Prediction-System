# Disease Prediction System using Machine Learning algorithms

# Explanation of Files

## training.csv

- This is the main dataset which has been used in this project. This dataset consist of mainly two columns "Disease" and "Symptoms" but this dataset is preprocessed so it helps in easily clasifying the data. This dataset is used to train the model.

## testing.csv

- This is the dataset which has been used to test the model for accuracy. This dataset is predefined with output.

## PythonCodeOfAlgorithm.py

This is the file which consist of dataset and there are various differnt algorithms used for training of the model which are as follows:

- Decision Tree
- Random Forest
- KNearestNeighbour
- Naive Bayes
  These four algorithms are used to train the model and give an accuracy of over 90

## Database

The database used in this project is "sqlite" whose name is database.db which consist of four tables in which the results of four different algorithms have been shown. The results of users with their names are being saved for future preferences.

## GUI.py

This is the file which is used to create the interface of the system. GUI stands for Graphical User Interface and Tkinter has been used to create it which gives a software kind of view to the project where user can directly interact with the system by entering the symptoms of dieases and they will get the prediction of disease through various algorithms.

## Project_ML.ipynb

This is the jupyter notebook which consist of complete code. This is used to explain the working of each and every module used in the project.

## GUI.jpeg

This file contains the screenshot of the built GUI which shows the working of the system

# Working with GUI

## Step 1:

Enter the name in the provided space infront of the label as "Name of the Patient". It is the mandatory field which user have to enter in order to get result.

## Step 2:

Select 5 Symptoms from the dropdown menu which are labelled as Symptom 1, Symptom 2, Symptom 3, Symptom 4, Symptom 5 respectively. If user is not aware of 5 symptoms then it is mandatory to enter atleast 2 starting systems, otherwise the result will not come and a message box will pop up for the same

## Step 3:

As per user interest, the disease can be predicted using different algorithms such as Decision tree algorithm, Random forest algorithm, Naive bayes algorithm and K-Nearest neighbour. Click on the respective buttons:</br>
Press Prediction 1 for Decision tree algorithm</br>
Press Prediction 2 for Random forest algorithm</br>
Press Prediction 3 for Naive bayes algorithm</br>
Press Prediction 4 for K-Nearest neighbour</br>
(User can predict the disease using more than one algorithm at a time)

## Step 4:

Disease Recommendation will be available infront of the labels of algorithm of user's choice.

## Step 5:

Click on "Reset" button to predict the disease for any other patient or Press "Exit System" button to come out of the GUI.

# A picture of GUI Interface
![gui1 2](https://github.com/R4hulD/Disease-Prediction-System/assets/101360312/b8d71f07-0aa2-4d92-9ec0-30a150c86ec8)
