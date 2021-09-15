# Logistic_regression

How does Logistic Regression work?

(let’s discuss with a real world example, also when to use linear regression and when logistic regression)

Let’s go with the good ol’ student example. To predict whether a student passed (1) or not (0). In this case, if we use simple linear regression, we will need to specify a threshold on which classification can be done.

Let say the actual class is the students who pass, and predicted continuous value is 0.85 and the threshold we have considered is 0.9, then this data point will be considered as the students who will fail and this will lead to the wrong prediction.

So we conclude that we can not use linear regression for this type of classification problem. As we know linear regression is bounded, So here comes logistic regression where value strictly ranges from 0 to 1.

Other examples could be:

To predict whether a person will buy a car (1) or (0)
To know whether the tumor is malignant (1) or (0)
How to implement logistic regression from scratch?

This is an implementation using numpy in Python.

My blog about logistic regression : https://smritimishra.in/2021/04/30/simple-logistic-regression-supervised-learning-algorithm/
