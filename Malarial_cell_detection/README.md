# Malarial Parasite detection
 [![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue.svg)](https://www.kaggle.com/tongpython/cat-and-dog) ![Python 3.7](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![TensorFlow](https://img.shields.io/badge/Library-TensorFlow-orange.svg)

## Demo

<p align='center'>
 
 <img src = "https://github.com/diwakarDrs/DeepLearning-Projects/blob/main/Malarial_cell_detection/ReadME/App.PNG" width = 600 alt="malaria">
 </p>

## About the app
> This project is a binary medical image classification model, based on convolutional neural network architecture.
The CNN has trained on the following malaria parasite image dataset  <a href="https://ceb.nlm.nih.gov/repositories/malaria-datasets/">National Library of Medicine</a>.
The trained model achieved accuracy of more than 95% on the test set and its weights have been saved in the Models folder (see file: my_model.h5). 


### Dependencies:
* Google Colaboratory / Jupyter Notebook
* Keras
* Tensorflow
* Python - 3.7
* Scikit-Learn
* Pandas
* Numpy
* Matplotlib
* Seaborn

### Data Augmentation
Using some Data Augmentation techniques for more data and Better results.
* Shearing of images
* Random zoom
* Horizontal flips


<p align='center'>
 
 <img src = "https://github.com/diwakarDrs/DeepLearning-Projects/blob/main/Malarial_cell_detection/ReadME/data.PNG" width = 600 alt="Data_Augmentation">
 </p>
 
 ### Network Parameter:
* Rectifier Linear Unit (ReLU) - Hidden Layers
* Sigmoid - Output Layer
* Adam optimizer
* Loss: Binary CrossEntropy

<p align='center'>
 
 <img src = "https://github.com/diwakarDrs/DeepLearning-Projects/blob/main/Malarial_cell_detection/ReadME/act.PNG" width = 600 alt="malaria">
 </p>

### Use other pre-trained model

See [Keras applications](https://keras.io/applications/) for more available models such as DenseNet, MobilNet, NASNet, etc.


## Deployment
To deploy in cloud, we can upload this app on heroku or other python enabled server. 


