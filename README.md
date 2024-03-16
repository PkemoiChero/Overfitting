# Overfitting
Machine Learning
This repository contains a synthetic dataset comprising 1500 instances tailored for a binary classification task. Class 1 is generated using three Gaussian distributions, each with means [6,14], [10,6], and [14,14], while Class 0 is derived from a uniform distribution spanning the range [0, 20]. The main objective is to showcase the application of a Decision Tree classifier in accurately classifying the instances.

For dataset generation, Python's NumPy and Matplotlib libraries are employed. The Decision Tree classifier is implemented utilizing the scikit-learn library. The dataset undergoes partitioning into training and testing sets, with the classifier trained on the former. Subsequently, the accuracy of the classifier is assessed on the test set.
