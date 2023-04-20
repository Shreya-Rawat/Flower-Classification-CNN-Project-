# Flower Classification CNN Project
## A Computer Vision Project

## DOMAIN: Botanical research 

## PROJECT OBJECTIVE:
To build a CNN classifier capable of determining a flower’s species from a photo.

## CONTEXT: 
University X is currently undergoing some research involving understanding the characteristics of flowers. They already have invested on curating sample images. They require an automation which cancreate a classifier capable of determining a flower’s species from a photo. 

## DATASET DESCRIPTION:
The data set comprises of images from 5 species of flowers daisy, tulip, rose, sunflower, and dandelion. Dataset can be downloaded from here https://www.kaggle.com/datasets/alxmamaev/flowers-recognition

- This dataset contains 4242 images of flowers.
- The data collection is based on the data flicr, google images, yandex images.
- This datastet is used to recognize flowers from the photo.
- The pictures are divided into five classes: chamomile, tulip, rose, sunflower, dandelion.
- For each class there are about 800 photos. 
- Photos are not high resolution, about 320x240 pixels. 
- Photos are not reduced to a single size, they have different proportions!

## Steps taken in the Project:
1. Loading and Understanding the data:
- Import the data. 
- Analyze the dimensions of the data. 
- Visualize the data. 
2. Data Preparation:
- Split the dataset into train and validation. 
- One hot encode the target variable. 
- Normalize the data. 
3. Train, tune, test, and Compare Deep Learning image classifier model using: 
- Use basic CNN for Training. 
- Then try various CNN with transferred learning models for training. 
- Save the best model. 
- Compare the results from the above steps and write your detailed observations. 
- Load the best fitted model and make the predictions on a test

## Conclusions:
From the accuracies of trained models and the above test example we can say that,
- Vgg19 is the best performing model and ResNet is the worst performing in our use case.
- For future improvements we can change the architecture of added layers and tune various hyperparameters for a range of other values.
- Also we can consider balancing our dataset for the 5 categories to avoid bias towards high frequncy class.
