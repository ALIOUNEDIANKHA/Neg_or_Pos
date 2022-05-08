# Neg_or_Pos
1 Logistic Regression

This assignment aims of implementing Logistic regression from scratch for multi-classication prob-
lem.

1.1 Setting
D = {(xi, yi)}
n_i=1, xi ∈ R^d , yi ∈ {−1, 1}.

In the case of binary classication, the loss function is given by the following crossentropy loss given
by:

 $\mathcal{l(\theta) } = \frac{1}{n}\sum_{i=1}^n \log (1+e^{ - y_ix_{i}^{T} \theta}) $ 


(1)

1. Show equation (1).
2. Use the iris dataset from scikit-learn and implement a multi-classication problem on it. The
iris dataset has three labels 0, 1, 2; Apply onehot encoding on them (1 for presence and

1

Page 2 over 2
−1 for absence, don't use 0 for absence).That means, if you have three classes, initially if
Y ∈ {0, 1, 2}
n
; After applying onehot encoding, Y becomes Y ∈ {−1, 1}
n×3
.

You have almost one week to work on this assignment. The deadline is Sunday 08 th
of May 2022 at midnight. Write the proof of equation (1) in the notebook you will
send. It will be nice for you to write modules or scripts for the code.
