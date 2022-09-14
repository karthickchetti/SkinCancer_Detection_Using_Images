# Melanoma Detection
> The objective of this project is to detect the different types of skin cancer using images from International Skin Imaging Collaboration(ISIC) dataset. Especially detecting melanoma,which is a type of cancer that can be deadly if not detected early because accounts for 75% of skin cancer deaths. This will help for early and quick diagnosis of the cancer types, thereby saving more lives using AI.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- Building a Convolutional Neural Network architecture which can detect 9 different types of skin cancer.
- Understanding the class imbalance in the data, and using advanced techniques like augmentation to prevent bias of the model towards classes with high images. Also to prevent overfitting, there needs to be measures taken while building the CNN model.
- Totally 3 models were built to as a result of optimization to come up with the best model for the dataset


## Conclusions
- Model 1 which was the initial built was simple and it used a conventional CNN architecture(simple) to classify the types of cancer classes, as expected, it gave a high train and low validation accuracy suggesting overfitting in the model
- Model 2 used keras Augmentation layers which reduced underfitting but it also reduced the training and validation accuracy, suggesting that there might be other problems such as class imbalance
- Model 3 uses an improved architecture inspired from conventional CNN architecture like VGG-16, but a simpler version, and 500 images were augmented for each class thereby balancing the classes and making the predictions unbiased, batch normalization and dropout layers ensured that overfitting issue is resolved
- Final model has training accuracy around 85% and validation accuracy around 75% thereby proving to be the best model amongst the 3 models built
- Future scope includes hyperparameter tuning such as learning rate change, tweaking the architecture and also running for more epochs so that the model stabilizes



## Technologies Used
- Augmentor
- Tensor flow
- Keras
- Numpy
- Matplotlib


## Contact
Created by [@karthickchetti] - feel free to contact me!