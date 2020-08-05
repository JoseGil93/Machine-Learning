# Machine Learning
* This Repository contains 3 Projects that I have developed in this Unit during my Master's Degree:
* I have developed the following projects in Python through Jupyter, Anaconda. 

1. [Image Recognition: PCA, Unsupervised Learning Project](https://github.com/JoseGil93/Machine-Learning/blob/master/SIT720_A1_218659676%20(2).pdf)

* In this project, the dataset contains 8x8 pixel images of 0-9 digits, as unstructured Data with more than 1.500 instance in every file. 
* An Unsupervised Learning Task was developed, by using K-Means algorithm with Euclidean Distance for Clustering and PCA for Dimensionality Reduction. 
* The PCA was plot represented in a Scatter Plot. 

2. [Breast Cancer Diagnosis and Handwritten digits Classifications: Binary and Multiclass Classification](https://github.com/JoseGil93/Machine-Learning/blob/master/Machine%20Learning%20A2%20Final.pdf)

* This Project consisted in 2 main parts, the first part is from a Dataset about Breast Cancer Diagnosis Data from Wisconsin, used in a Kaggle Competition. For the First part of this
project, the data was explored and feature engineering was applied by using normalization and standardizaton. Secondly, 2 logistic Regression models 
were trained with certain parameters and tested with the performance metrics. Then, there was a hyperparameter tuning and the results of the performance metrics such as 
Precicion, Recall, Accuracy, Confusion Matriz, were compared. 

* For the second main part, Multiclass Classification, it was used an unstructured data of handwritten digits. Thus, descriptive statistics was performed with data exploration, 
then the data was split for training the data using Logistic Regression for multiclass classification of Supervised Learning, and the models were optimised by tuning the hyperparameters, in
which the performance metrics shows the results obtained. 

3. [Human Activity Recognition using Smartphones: Supervised Learning Project](https://github.com/JoseGil93/Machine-Learning/blob/master/218659676%20Assignment%204%20ML%20(2).html.pdf)

* It is a human activity Recognition Problem. 
* The data was gathered from a experiment of 30 volunteers between 19-48 years old, each volunteer had to perform 6 activities while they were wearing a smartphone to track the sensors signals such as acelerometer and gyroscope, the acceleration signal has a gravitational force and body motion components. 
* Therefore, from a Training dataset of more than 7.000 instances and Testing dataset of more than 2.500 instances, compiled in txt files as digits of unstructured data, it was required to develop 5 algorithms in order to solve this problem. First of all, it was implemented K-NN, K-Nearest neighbour, and each k was cross-validated with 10 k-fold, the results were evaluated form the performance metrics. Secondly, it was implemented a Multiclass Logistic Regression with Elastic Net and the model was also optimised. 
* Thirdly, a SVM or Super Vector Machine algowithm was performed, applying it with a RBF Kernel and tunning the gamma and C parameters in order to obtain the best results from a well trained data. The results of the predictions were evaluated with the f1-score, accuracy, confusion matrix, performance metrics. 
* Finally, a Random Forest algorithm was implemented for classifying the data accurately and the hyperparemeters such as tree-depth were optimised. After evaluating the performance metrics of every algorithm, it helped to decide the best performer algorithm for this Classification Problem. 
