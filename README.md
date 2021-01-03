# Dimensionality-Reduction-Python

Dimensionality reduction is a process where we reduce the number of features to be analyzed, thus reducing the cost for analysis of data. The data used ia a synthetic data of plant genetics. Here, we select 15 causal features from a total of 29,623 features using Pearson's Correlation. After feature selection, we perform classification on this new dataset using machine learning packages by implementing SVM, Gaussian  Naïve Bayes, Logistic Regression and Nearest Centroid techniques to compare the accuracy of predictions given by this new dataset.

## Step 1. Download Training Data and Labels from following links into the main folder

https://drive.google.com/file/d/1VEDZij2y1N_uNLHxiAG_VYBxO4u49GPC/view?usp=sharing    ### Training Data

https://drive.google.com/file/d/1P_vYq5qYQ5aJptx-J1FcHBDG8ndqsGD9/view?usp=sharing    ### Training Label

## Step 2. Download and unzip the test data into the main folder

## Step 3. Execute the following command

python DimensionalityReduction.py traindata trainingLabels.txt testdata
