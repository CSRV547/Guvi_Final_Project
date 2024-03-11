 1. Extract the dataset from the npz file from the downloaded dataset or from the web.There are
 60000 images for training and 10000 images for test. Each image is of the size 28X28.
 2. Perform PCA to 10 components. So now we have train and test images in 10 dimension instead
 of 28X28 dimension.
 3. Nowapply the the following models:
 • Decision Trees
 • Random forest
 • Naive Bayes Model
 • K-NNClassifier
 • SVM
4. For each of this method produce the following metrics:
 • Precision, Recall, F1- Score
 • Confusion Matrix
 • RoC-AUCcurve
 5. Try to repeat the same experiment for different component size : 15,20,25,30
