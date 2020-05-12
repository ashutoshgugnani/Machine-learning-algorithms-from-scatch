# Machine-learning-algorithms-from-scatch
Binary Bayes classifier 
 
Bayes classifiers under assumptions below, and   ML estimators to compute and return the results on a test set. 

1a) Assume $X|Y=-1 \sim \mathcal{N}(\mu_-, I)$ and  $X|Y=1 \sim \mathcal{N}(\mu_+, I)$. *(Same known covariance)*

1b) Assume $X|Y=-1 \sim \mathcal{N}(\mu_-, \Sigma)$ and $X|Y=1 \sim \mathcal{N}(\mu_+, \Sigma)$ *(Same unknown covariance)*

1c) Assume $X|Y=-1 \sim \mathcal{N}(\mu_-, \Sigma_-)$ and $X|Y=1 \sim \mathcal{N}(\mu_+, \Sigma_+)$ *(different unknown covariance)*


Logistic regression :
Code for logistic regression below. Also code for choosing best hyperparameters for each kernel type (using a part of training set as validation set). 

The range of hyperparameters is typically chosen on a log scale e.g. 1e-4, 1e-3, 1e-2... 1e3.

For each classification data set reported the best kernel and regularisation parameters for linear, RBF and Poly kernels. (Linear has no kernel parameter.) Reported the training and test zero-one error for those hyperparameters. 

For the synthetic classification datasets (dataset_A and dataset_B) in 2-dimensions, also illustrated the learned classifier for each kernel setting. Do this in the last codeWrite cell for this question.

