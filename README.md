# Convolutional Neural Network to predict if a Patient has COVID
Building a Convolutional Neural Network to detect whether a patient has COVID from X-ray images.

This project was built for University of Georgia's CSCI 4360(Data Science 2) Class. 

Author: 
- Steven Zhang, University of Georgia
- Chenqian Xu, University of Georgia
- Xin He, University of Georgia

# Project Overview
The dataset for this project can be found on Kaggle [here](https://www.kaggle.com/datasets/khoongweihao/covid19-xray-dataset-train-test-sets).

We have an image classfication problem. Given X-ray images already labeled whether a patient has COVID, Pnemonia, or is Healthy, we want to create a Machine Learning Model to generate corresponding predictions on new X-ray images on if a patient has either COVID, Pnemonia, or is Healthy. Therefore, we implement a Convolutional Neural Network specializing in dealing with Image Classification tasks.

The [COVID Classification CNN Workshop.ipynb](https://github.com/stevenzhang070302/COVID-CNN-Model/blob/main/COVID%20Classification%20CNN%20Workshop.ipynb) file is the notebook containing all our code for using TensorFlow's layers package to construct a Convolutional Neural Network to predict whether a patient has COVID based on their X-ray image.

# Project Outcome
Below we can see the loss graphs from training the Convolutional Neural Network, Confusion Matrix of predictions made to the Validation dataset, and predictions made to new never-seen-before X-ray images.

![CNN_Loss_Graph](https://github.com/stevenzhang070302/COVID-CNN-Model/blob/main/CNN_Loss_Graph.png)

![CNN_Confusion_Matrix](https://github.com/stevenzhang070302/COVID-CNN-Model/blob/main/CNN_Confusion_Matrix.png)

![CNN_Predictions](https://github.com/stevenzhang070302/COVID-CNN-Model/blob/main/CNN_Pred.png)
