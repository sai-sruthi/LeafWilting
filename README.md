# LeafWilting
Leaf Wilting Detection in Soybean using Neural Networks

The data set we worked on comprises of soybean plant images through at different times of the day. 
The aim of the project is to identify the level of wilting that is observed in all the images. 
The level of wilting has been classified into 5 groups. 
The data set consists of 1,275 total images in the training data set. 
The test data consists of 200 images. The distribution of the images in training data is imbalanced. 
In second phase of the project we have tried to use various pretrained models for feature extraction. 
This would help in identifying the most important features from the given images and then form a data set on which neural network model is trained. 
As a part of of our project the various convolutional neural networks that we tried are VGG16, VGG19 and Resnet for feature extraction from our images. 
Further, we have used techniques like SMOTE and hyper parameter tuning to balance the data and get best parameters for training models respectively.
The features that we extract by using the pre trained models are fed into a convolutional neural network for actual image classification. 
After testing all different types of pre-trained architecture we found that VGG19 performed the best in our case and hence 
has been used to make the final prediction for the test dataset.


The data for the project can be found in the below link : 
https://drive.google.com/drive/folders/1haDgwOe-OyHbBqun-twTPAY8914oQWrT?usp=sharing
