# CS867-Assignment-3-Image-Classification-using-CNN
This repository contains files related to the CS867 Assignment 3.

## Tools and Dataset Used
1. Google Colaboratory
2. Image Classification Dataset is used from Kaggle https://www.kaggle.com/puneet6060/intel-image-classification/version/2.
3. Dataset is used via gdrive in colab.

## Methodology

#### Augmentation
Following augmentations are applied with different parameters settings during the training of the model:
1. Rescale
2. Rotation
3. Horizontal Flip
4. Brightness

## Training
VGG16 model is used to learn the results of augmentation on dataset with adaptive learning rates and see it's difference from the base modd. The code is avaiable in the directory. Weights file is stored in gdrive which you can access from here: https://drive.google.com/file/d/1i07HOD3_bpaH8OiSEPj5j3QrtVxuT00R/view?usp=sharing

## Results
An accuracy of 0.9 and loss of 0.3 was achieved in the experimentation.

#### Accuracy
![alt text](https://github.com/mkhalilSEECS/CS867-Assignment-3-Image-Classification-using-CNN/blob/main/accuracy.PNG?raw=true)
#### Loss
![alt text](https://github.com/mkhalilSEECS/CS867-Assignment-3-Image-Classification-using-CNN/blob/main/loss.PNG?raw=true)
