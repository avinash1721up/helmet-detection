# HELMET DETECTION
This model detects the helmet of workers whether they are wearing helmets or not in a particular , may be a dangerous workspace where helmets are neccessary.It uses the implementation of Deep Learning , Keras and OpenCV for the training of the  model.Note that this model only runs on GPU

![images1](https://user-images.githubusercontent.com/68318221/92746230-b1b57e80-f3a0-11ea-957c-ffd9fae0023d.png)      ![download1](https://user-images.githubusercontent.com/68318221/92746706-1e307d80-f3a1-11ea-90e0-bb139c6caf2d.png)              ![download5](https://user-images.githubusercontent.com/68318221/92747161-8f703080-f3a1-11ea-9dd1-e13588c23096.png)






## PRE-REQUISITES 

For Windows

- Anaconda Navigator

- OpenCV 

- Tensorflow(Keras included)





### STEPS FOR CREATING THE MODEL
The whole process for helmet detection using Keras can be divided in following  major steps:

a. Upload the dataset(from Kaggle). Click [here](https://www.kaggle.com/andrewmvd/hard-hat-detection "HD") to see it. The dataset consists of 5000 images and also contains the      xml file with two classes: one having helmet and other not having helmet.

b. Detect helmet in an image using Keras and OpenCV

c. Convert image into grayscale(given in RGB form) 

d. Design convolutional neural network using Keras

e. Train the model on the test model on testing data after doing Image Augmentation

f. Import the optimizer and load_model for compiling and saving the model in HDF







#### EXPLANATION OF  CREATED MODEL





The model architecture is a linear sequence of layer transformations of the following types:

• Convolution + ReLU activations

• MaxPooling

• Sigmoid

Keras is a high-level library, used specially for building neural network models. It is written in Python and is compatible with both Python – 2.7 & 3.5. Keras was specifically developed for fast execution of ideas. It has a simple and highly modular interface, which makes it easier to create even complex neural network models. This library abstracts low level libraries, namely Theano and TensorFlow so that, the user is free from “implementation details” of these libraries.



Convolutional Neural Networks (ConvNets or CNNs) are a category of Neural Networks that have proven very effective in areas such as image recognition and classification.

There are four main operations in the ConvNet:

• Convolution

• Non Linearity (ReLU)

• Pooling or Sub Sampling

• Classification (Fully Connected Layer)


These operations are the basic building blocks of every Convolutional Neural Network, so understanding how these work is an important step to developing a sound understanding of ConvNets.





##### OPENCV



OpenCV (Open Source Computer Vision Library) is a library of programming functions mainly aimed at real-time computer vision.The library is cross-platform and free for use under the open-source BSD license.


The saved keras model is used here in opencv and by using  upper body classifier , the model is giving the predicted results as






                   ![images3](https://user-images.githubusercontent.com/68318221/92759051-f3e4bd00-f3ac-11ea-95cd-4bf889f20862.png)



This library helps us to work and mainly detect some real time images so that we can assure that our model is working fine or not.




**MY EXPERIENCE**

- YOLO is definitely a better option for the working of these type of object detection models. I tried to implement this model by YOLO as well but laptop features didnt allowed it.

- I searched and gained some extra and beneficial skills in this project. Hopefully , this model worked according to my expectations.















     

