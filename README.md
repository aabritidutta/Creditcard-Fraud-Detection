# Creditcard-Fraud-Detection
Predict if a transaction is a fraud transaction or not, also, dealing with imbalanced data and finding the pattern using correlation between the features.

**Imbalanced Classification Problems**
The number of examples that belong to each class may be referred to as the class distribution.

Imbalanced classification refers to a classification predictive modeling problem where the number of examples in the training dataset for each class label is not balanced.

That is, where the class distribution is not equal or close to equal, and is instead biased or skewed.

Imbalanced Classification: A classification predictive modeling problem where the distribution of examples across the classes is not equal.
For example, we may collect measurements of flowers and have 80 examples of one flower species and 20 examples of a second flower species, and only these examples comprise our training dataset. This represents an example of an imbalanced classification problem.

An imbalance occurs when one or more classes have very low proportions in the training data as compared to the other classes.

**Overview**

- Get familiar with class imbalance
- Understand various techniques to treat imbalanced classes such as-
- Random under-sampling
- Random over-sampling
- NearMiss
- 
You can check the implementation of the code in my GitHub repository

**Introduction**
When observation in one class is higher than the observation in other classes then there exists a class imbalance. Example: To detect fraudulent credit card transactions. As you can see in the below graph fraudulent transaction is around 400 when compared with non-fraudulent transaction around 90000.
![image](https://user-images.githubusercontent.com/79006607/133974648-8fdf4c8d-caa5-4624-8ba0-19ba7ad28daa.png)

Unfortunately, here accuracy will be misleading.

All those non-fraudulent transactions, you’d have 100% accuracy.
Those transactions which are fraudulent, you’d have 0% accuracy.
Your overall accuracy would be high simply because the most transaction is not fraudulent(not because your model is any good).
This is clearly a problem because many machine learning algorithms are designed to maximize overall accuracy. In this implementation, we will see different techniques to handle the imbalanced data.

