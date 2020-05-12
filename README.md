# Machine-learning-algorithms-from-scatch
## 1.Binary Bayes classifier 
 
Bayes classifiers under assumptions below, and   ML estimators to compute and return the results on a test set. 

1a) Assume P(X|Y)=-1 | Normal distribution | Same known covariance

1b) Assume P(X|Y)=-1 | Normal distribution | Same unknown covariance

1c) Assume P(X|Y)=-1 | Normal distribution | Different unknown covariance


## 2.Logistic regression :

Code for logistic regression below. Also code for choosing best hyperparameters for each kernel type (using a part of training set as validation set). 
The range of hyperparameters is typically chosen on a log scale e.g. 1e-4, 1e-3, 1e-2... 1e3.
For each classification data set reported the best kernel and regularisation parameters for linear, RBF and Poly kernels. (Linear has no kernel parameter.) Reported the training and test zero-one error for those hyperparameters. 
For the synthetic classification datasets (dataset_A and dataset_B) in 2-dimensions, also illustrated the learned classifier for each kernel setting.


## 3.Support Vector Machine :

Code for learning SVM . Code for choosing best hyperparameters for each kernel type. Used sklearn.svm for this purpose. (used a part of training set as validation set)

For each classification data set reported the best kernel and regularisation parameters for linear, RBF and Poly kernels. (Linear has no kernel parameter.) Reported the training and test zero-one error for those hyperparameters.

For the synthetic classification datasets in 2-dimensions, also illustrated the learned classifier for each kernel setting.


## 4. Decision Tree

Code for learning decision tree below. Taken as an argument a hyperparameter on what size node to stop splitting. Used a part of training set as validation set. 
For synthetic data sets (dataset A and dataset B) reported the best node size to stop splitting. Reported the training and test zero-one error for those hyperparameters.
For datasets A and B, also illustrated the learned classifier.


## 5.Random Forest classifier

Code for learning RandomForests below

For all 4 data sets (A,B,C,D)  reported the best number of trees found. Reported the training and test zero-one error for those hyperparameters.
