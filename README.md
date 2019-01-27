# Advanced_learning

The purpose of this project is to study and reproduce the results of the paper "Explicit Inductive Bias for Transfer Learning with Convolutional Networks".
Our implementation will be based on ResNet50 (instead of ResNet101 used in the paper) to compare several types of regularization.
The source databases in use are ImageNet and Places 365 and the target databases are Caltech 256, MIT Indoors 67 and Stanford Dogs 120.
We are using Keras for ResNet50 pretrained on ImageNet and PyTorch for ResNet50 trained on Places 365.
