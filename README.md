# COMP551-Project1 KNN and Decision Trees
In this project, we implemented two classiﬁcation techniques—K-Nearest Neighbour and Decision Trees from scratch and compare these two algorithms on two distinct health datasets.

# Dataset
• Dataset 1: breast cancer wisconsin.csv (Breast Cancer dataset):
https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)
• Dataset 2: hepatitis.csv (Hepatitis dataset):
http://archive.ics.uci.edu/ml/datasets/Hepatitis

# Implement the models
Implement the models from scratch (i.e., you CANNOT use SciKit Learn or any other pre-existing implementations of these methods).
Regarding the implementation, we recommend the following approach (but again, you are free to do what you want):
• Implement both models as Python classes. You should use the constructor for the class to initialize the model parameters as attributes, as well as to deﬁne other important properties of the model.
• Each of your models classes should have (at least) two functions:
    – Deﬁne a fit function, which takes the training data (i.e., X and Y)—as well as other hyperparameters (e.g., K value in KNN and maximum tree depth in Decision Tree)—as input. This function should train your model by modifying the model parameters.
    – Deﬁne a predict function, which takes a set of input points (i.e., X) as input and outputs predictions (i.e., y) for these points.
• In addition to the model classes, you should also deﬁne a functions evaluate_acc to evaluate the model accuracy.
    - This function should take the true labels (i.e., y), and target labels (i.e., y) as input, and it should output 
# Run experiments
Split each dataset into training and test sets. Use test set to estimate performance in all of the experiments after training the model with training set. Evaluate the performance using accuracy. At a minimum you must complete the following experiments:
  1. Compare the accuracy of KNN and Decision Tree algorithm on the two datasets.
  2. Test different K values and see how it affects the training data accuracy and test data accuracy.
  3. Similarly, check how maximum tree depth can affect the performance of of Decision Tree on the provided datasets. Describe your ﬁndings.
  4. Try out different distance/cost functions for both models. Describe your ﬁndings.
  5. Present a plot of the decision boundary for each model. Describe the key features in short.
