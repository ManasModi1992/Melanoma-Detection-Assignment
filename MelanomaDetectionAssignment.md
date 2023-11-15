# Project Name
> To build a CNN based model which can accurately detect melanoma

## Table of Contents
* [General Info]
* [Technologies Used]
* [Conclusions]
* [Acknowledgements]

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases
- All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- Findings from Model1
From the graph we can see training accuracy is very high as compared to validation accuracy. We can also see difference in loss functions in training and validation data around 19th and 20th epochs. This is a clear case of overfitting where model has learned too much from training dataset and it is not able to perform well on the validation dataset.

Training Accuracy: 88.90
Validation Accuracy: 53.02

- Findings from Model 2
Accuracy of trainings has not improved as compared to base model but gap between training accuracy and validation accuracy is reduced. Also validation accuracy is increased slightly compared to base model. Gap between loss of training and validation is also reduced. And we observe that overfitting issue has been reduced due to data augmentation.

Training Accuracy: 61.83
Validation Accuracy: 54.36

- Findings from Model 3
Accuracy of training and validation has been increased significantly due to augmentation and class imbalnce handling. The model is not overfitting. This model can be used as final model.

Training Accuracy: 94.12
Validation Accuracy: 83

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- numpy
- tensorflow
- matplotlib 
- pathlib

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by IIITB and Upgrad


## Contact
Created by [@ManasModi1992] - feel free to contact me!
