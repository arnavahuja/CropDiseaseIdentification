# Crop Disease Identification

## Introduction
As a deep learning enthusiast, this project was undertaken to explore the intricacies of image classification and make it better. This project aims to increase the accuracy in crop disease identification by creating a new custom defined model inspired from the resnet as well as the inception net structure.

## Approach/Methodology Used
* The resnet structure was initially used for crop disease identification as it is a celebrated structure for image classification tasks.
* We then made a custom model, inspired from the resnet architecture as well as the inception architecture using both of them to our advantage.
* The resnet architecture has its unique skip-connections which are useful in solving the problem of vanishing and exploding gradients. 
* The inception resnet has its unique 1x1 convolutions which allows us to use multiple filters without increasing the number of parameters.

## Results
* We were pleased to see that our new custom model gave an accuracy of 98.16% which was more than the one given by the original resnet model (97.5%) for the plant village dataset.
* For the plant doc dataset the original accuracy was very low of about 30%. Augmentation of images and creation of the new dataset increased the accuracy significantly to 66.06%  (inception resnet architecture)
* We believe the this model can be used for other tasks as well and give a great accuracy too.
