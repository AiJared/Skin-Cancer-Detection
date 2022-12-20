# Skin-Cancer-Detection
A deep learning project for skin cancer detection using tensorflow.

Given a dataset of skin cancer images, this project classifies skin cancer tumors into either benign or malignant.

The model is fit into the dataset then trained to identify whether a tumor is benign or malignant.

Below is an image of a benign tumor,

![Screenshot 2022-12-20 160134](https://user-images.githubusercontent.com/78556152/208673808-01551a4a-d57f-4e5d-9f31-f75e1eab8b47.png)

Malignant tumor.

![malig](https://user-images.githubusercontent.com/78556152/208674041-0d6a73ab-d9f6-4a65-8ba7-732c0fa666b6.jpg)

## Splitting into Training and Validation

Some parameters are first defined for the loader:

batch size set to 32,

Image height set to 180 and 

Image width set to 180.

The dataset is split into training set and validation set with 80% given to training set and 20% given to validation for better learning.

## Classes

There are two classes; benign class and malignant class as shown below

![Screenshot 2022-12-20 161200](https://user-images.githubusercontent.com/78556152/208675418-a31538b4-dd5e-4dd0-bd16-0cb928e032ce.png)


