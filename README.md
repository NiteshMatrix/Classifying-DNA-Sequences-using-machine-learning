# Classifying-DNA-Sequences-using-machine-learning
This is a Python code for classifying DNA sequences using various classification algorithms. The dataset used is from the UCI repository, containing promoter gene sequences.

## Step 1: Importing the Dataset
The code starts by importing the necessary libraries and fetching the dataset from the UCI repository as a Pandas DataFrame. The dataset is then printed to check the first row of the DataFrame.

## Step 2: Preprocessing the Dataset
The data is not in a usable form, so it needs to be processed before being used to train the algorithms. A custom Pandas DataFrame is built for each column in the dataset. The DNA sequences are split into individual nucleotides and the class assignments are appended. The dataset is then turned into a Pandas DataFrame and transposed for clarity. The last column is then renamed to 'Class'. The data is then converted to numerical format using the pd.get_dummies() function. One of the class columns is dropped, and the remaining column is renamed to 'Class'. Finally, the data is split into training and testing datasets using the model_selection module.

## Step 3: Training and Testing the Classification Algorithms
Now that the data has been preprocessed and the training and testing datasets have been built, various classification algorithms can be used to classify the DNA sequences. Ten different algorithms are used and the performance of each is compared and contrasted. The accuracy score and classification report are used as performance metrics. The code defines each algorithm and evaluates them in turn using cross-validation.

## Step 4: Model Evalution
Classification Algorithms
The project compares and contrasts the performance of ten different classification algorithms on the DNA promoter classification problem. The algorithms used in the project include:

K Nearest Neighbors
Gaussian Process
Decision Tree
Random Forest
Neural Net
AddaBoost
Naive Bayes
SVM Linear
SVM RBF
SVM Sigmoid
The models are evaluated using accuracy score and classification report.

This code is useful for anyone interested in bioinformatics or machine learning classification algorithms. The code can be used as a starting point for DNA sequence classification or as a reference for implementing and comparing different classification algorithms.
