# CIFAR-10-CNN-ONE-BATCH

Implementation of two models in Keras for the classification of the CIFAR-10 dataset.

First model

It's a simple model with three Convolution+Max Pooling+Dropuout layers and two fully-connected layers. It has a validation accuracy of 78%.

Second model

The second model uses augmentation and three different types of normalization:

Batch normalization
Kernel regularization
Dropout
I also use a learning rate scheduler to change the lr in the middle of the training
