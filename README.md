# Naive_Bayes
In this project, we will develop a machine learning model for SMS spam detection using the Naive Bayes algorithm. The goal is to create a system that can automatically classify incoming text messages as either spam (unsolicited or unwanted) or ham

# Bayes' Theorem
Naive Bayes is based on Bayes' Theorem, which is a fundamental theorem in probability theory. Bayes' Theorem describes how to update the probability for a hypothesis (a model or a class label) based on new evidence (features or data).

In the context of classification, we are interested in finding the probability of a particular class (C) given some observed features (X)

# P(C∣X)= P(X∣C)⋅P(C) / P(X)

Here's what each term represents:
P(C∣X) is the posterior probability of class C given the features X.
P(X∣C) is the likelihood of observing the features X given class C.
P(C) is the prior probability of class C.
P(X) is the probability of observing the features X

# Naive Bayes Assumption
The "naive" assumption in Naive Bayes is that features are conditionally independent, meaning that the presence or absence of one feature does not affect the presence or absence of another feature. This assumption simplifies the calculations significantly. While it may not hold true in all real-world scenarios, Naive Bayes often performs surprisingly well despite this simplification



​
 

