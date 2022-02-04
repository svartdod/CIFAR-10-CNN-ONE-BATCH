# CIFAR-10-CNN-ONE-BATCH

Implementation of two models in Keras for the classification of the CIFAR-10 dataset using only one batch of dataset.

First model

It's a simple model with three Convolution+Max Pooling+Dropuout layers and two fully-connected layers. It has a validation accuracy of 83%.

Second model

The second model uses augmentation and two different types of normalization . It has a validation accuracy of 90%:

Kernel regularization
Dropout


Third Model 

The thid model use augmentation and three diffrents type of normalization . It has a validation accuracy of 93%: 

Kernel regularization
Dropout
BatchNormalization 


I also use a learning rate scheduler to change the lr in the middle of the training
