# Wild Fire-and-No-fire-Image-classification
Inception model is trained to classify the fire and no fire forest images.

## Problem statement
Data was collected to train a model to distinguish between the images that contain fire (fire images) and regular images (non-fire images), so the whole problem was binary classification.

## Dataset
Data is divided into 2 folders, fireimages folder contains 755 outdoor-fire images some of them contains heavy smoke, the other one is non-fireimages which contain 244 nature images (eg: forest, tree, grass, river, people, foggy forest, lake, animal, road, and waterfall).

Hint: Data is skewed, which means the 2 classes(folders) doesn't have an equal number of samples, so make sure that you have a validation set with an equally-sized number of images per class (eg: 40 images of both fire and non-fire classes).
link to dataset :https://www.kaggle.com/phylake1337/fire-dataset

## Install required
* Keras
* Tensorflow
* numpy
* pandas
* matplotlib

## Results
Inceptionv3 model really performed well on binary classification and 97% validation accuracy is achieved
[results](https://github.com/nb20593/Fire-and-No-fire-Image-classification/blob/main/Loss%20vs%20Accuracy.png)
