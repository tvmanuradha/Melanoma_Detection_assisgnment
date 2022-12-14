# Melanoma Detection Assignment

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
## Problem Satement
- To build a CNN based model which can accurately detect melanoma.
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
- A machine learning solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. sell at maximum profits.
- Hence,
- Goals of Study
- To build a multiclass classification model using a custom convolutional neural network in TensorFlow.

## Approach
- We will build a baseline CNN model first and tune it on the validation set.
- We will check for underfitting / overfitting of model and improve it using Augmentation of the training data.
- We will check for class imbalance of the model and improve it generating more images of each class.

## Conclusions
1) The model has achieved maximum training accuracy of 81.97% and validation accuracy of 76.76%.
2) There is less overfitting than before as training and validation accuracy are closer than before. The accuracy for both training and validation decrease gradually together.
3) The loss for both training and validation decrease gradually together as well.
4) After reducing class imbalance, tuning the learning rate, the accuracy has increases significantly and also solved problem of overfitting.

## Technologies Used
- pandas - version 1.2.4
- numpy - version 1.20.1
- seaborn - version 0.11.1
- matplotlib - version 3.3.4
- python - version 3.6.3
- statsmodels.api - version 0.12.2
- sklearn - version 0.24.1
- Tensorflow version 2.8.0
- Keras version 2.8.0


## Acknowledgements
Give credit here.
- This project is inspired by upgrad
- stackoverflow

## Contact
Created by [@tvmanuradha] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->