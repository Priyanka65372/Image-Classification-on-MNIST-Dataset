# Image-Classification-on-MNIST-Dataset
This project focuses on image classification using the MNIST dataset, a collection of handwritten digits.
 The classification is performed using the K-Nearest Neighbors (KNN) classifier, and optimal hyperparameter values are determined using XGBoost and a Voting Classifier. The combination of models aims to enhance the accuracy and robustness of the classification task.

Key Components
MNIST Dataset:

The MNIST dataset is a collection of 28x28 pixel grayscale images of handwritten digits (0 to 9). It is widely used for training and testing image classification models.
K-Nearest Neighbors (KNN) Classifier:

The KNN classifier is employed for image classification. It is a simple and effective algorithm that classifies a data point based on the majority class of its k-nearest neighbors.
XGBoost for Hyperparameter Tuning:

XGBoost is utilized to find optimal hyperparameter values for the KNN classifier. A grid search is performed to identify the combination of hyperparameters that maximizes classification performance.
Voting Classifier:

A Voting Classifier is implemented to combine the predictions of the KNN classifier with those from the tuned XGBoost model. The ensemble approach aims to leverage the strengths of individual models for improved accuracy.

An accuracy of 96.94% was achieved.
