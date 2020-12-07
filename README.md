# k-Nearest Neighbor
## Assignment 3 - Introduction to Artificial Intelligence
You are given dataset of Pima India Diabetes Dataset (PIDD) in file Diabetes.csv. The dataset contains 768 data objects (rows). Create five new datasets using the 5-fold cross-validation scheme. First, divide the data object into equal portions of five subsets, each containing one fifth (20%) of the data. Then, create five new datasets with the composition of the data objects in the training set and testing set as follows:
1. Row 1 to line 614 as a training set and the rest as a testing set;
2. Row 1 to line 461 plus lines 642 to 768 as a training set and the others as a testing set;
3. Row 1 to line 307 plus lines 462 to 768 as a training set and the others as a testing set;
4. Row 1 to line 154 plus lines 308 to 768 as a training set and the others as a testing set; and
5. Lines 155 to 768 as training sets and the others as testing sets.
Analyze, design, and implement the k-nearest neighbor (kNN) algorithm into a computer program. Select and estimate the kNN model using 5-fold cross-validation which produces the highest accuracy.
Output of the system:
* Best k value of kNN learning; and
* Average accuracy of kNN using 5-fold cross-validation.