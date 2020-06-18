# Digit Recognition using Convolutional Neural Networks

This is a digit recognition model using a Convolutional Neural Network giving an accuracy of over 99.4% (max recorded accuracy @ 99.6%)

The architecture for this network is:

Input -> [Conv2D -> ReLu -> Conv2D -> ReLu -> MaxPool2D -> Dropout]*2 -> Flatten -> Dense -> Dropout -> Output

(Architecture inspired from Yassine Ghouzam's Kaggle article)