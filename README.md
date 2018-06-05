Unsupervised anonymized shell sessions clustering
=================================================

The goal of this project is to estimate the number of users on a remote machine from anonymized session shell commands over a multi-year period.

The dataset is drawn from the command history of an unknown number of UNIX computer users over a multi-year period.
It has been sanitized to remove identifying attributes such as timestamps, user and file names as well as directory structures. The output of the program predicts within a degree of certainty how many users comprise the dataset.

![Result figures](https://github.com/percevalw/ShellUsersClustering/raw/master/doc/figure.png)
*On the left, estimation of the number of topics to use using word perplexity*   
*On the right, estimation of the number of users using bic score on the gaussian mixture results*
