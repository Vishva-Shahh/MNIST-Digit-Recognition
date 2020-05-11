# MNIST-Digit-Recognition

You need to download its training and data from http://www.kaggle.com/c/digit-recognizer. 
Refer to the kaggle competition page that describes the format of the dataset. Our goal is
to classify each digit as correctly as possible.
(a) Code a function that displays at least one image per each digit.
(b) Measure the distribution over the labels in the training data. (Hint: This is often called
the prior probability of the classes). Report whether each label is uniformly distributed
across the training examples.
(c) Implement a multiclass classification via logistic regression and try to vary the parameters
so that you can achieve the best performance on our Kaggle dataset. (Hint: Feel free to
refer to the code,2 but note that you should use the dataset downloaded from Kaggle!)
(d) Implement a neural-net classifier with varying the number of hidden layers and neurons
there. Compare the performance with the result from (c). Report the interesting images.
For example, if the number `3' is the label with the lowest precision, the incorrectly
labeled as `3' that must not be `3' (i.e., false positives) and the incorrectly labeled as
other than `3' that was supposed to be `3' (i.e., false negatives)) will provide good sources
to observe interesting images.
