<h1 align="center"> Clean Vs Messy Rooms Classifier using Tensorflow </h1>

<p align="center">
    <img src="https://i.imgflip.com/5im1am.jpg" width="800">
</p>

## Overview
In this project, the task is to classify the image of a room as clean or messy. The model architecture is built using the Convolutional Neural Network (CNN) from the Tensorflow library.

## Dataset
The data set for this project was obtained from [Kaggle](https://www.kaggle.com/cdawn1/messy-vs-clean-room). Pictures consist of two classes, clean and messy rooms. There are 192 images in the training set (96 per class); 20 images (10 per class) in the validation set; 10 images (5 per class) in the test set. The location is diverse, including bedrooms, living rooms, dining rooms, study rooms and kitchens, which might help to discourage the model from capturing unrelated features but instead focus more on the "messiness".

## Work Steps
<ol>
  <li>Import library</li>
  <li>Download and extract file</li>
  <li>Separate training and validation set</li>
  <li>Data pre-processing using image augmentation</li>
  <li>Prepare train data</li>
  <li>Building a model architecture with CNN</li>
  <li>Create Callbacks</li>
  <li>Plotting accuracy and loss</li>
  <li>Predict image</li>
</ol>  

## Model Summary

Model: "sequential"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
conv2d (Conv2D)              (None, 148, 148, 32)      896       
_________________________________________________________________
max_pooling2d (MaxPooling2D) (None, 74, 74, 32)        0         
_________________________________________________________________
conv2d_1 (Conv2D)            (None, 72, 72, 64)        18496     
_________________________________________________________________
max_pooling2d_1 (MaxPooling2 (None, 36, 36, 64)        0         
_________________________________________________________________
conv2d_2 (Conv2D)            (None, 34, 34, 128)       73856     
_________________________________________________________________
max_pooling2d_2 (MaxPooling2 (None, 17, 17, 128)       0         
_________________________________________________________________
conv2d_3 (Conv2D)            (None, 15, 15, 512)       590336    
_________________________________________________________________
max_pooling2d_3 (MaxPooling2 (None, 7, 7, 512)         0         
_________________________________________________________________
flatten (Flatten)            (None, 25088)             0         
_________________________________________________________________
dense (Dense)                (None, 128)               3211392   
_________________________________________________________________
dense_1 (Dense)              (None, 1)                 129       
=================================================================
Total params: 3,895,105
Trainable params: 3,895,105
Non-trainable params: 0
_________________________________________________________________

## Visualize Accuracy and Loss 
![training and loss metrics](images/accuracy_loss.JPG)

## Predict Model
<p align="left">
    <img src="images/predict.JPG" width="500">
</p>
