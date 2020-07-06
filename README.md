# Face-Recognition-Model-using-Deep-Learning
Face Recognition Model using Deep Learning technique know as Deep metric Learning

Perform face recognition in both images and video cam streams using:

**OpenCV**

**dlib**

**Python**

**Deep learning**

The deep learning-based facial embeddings are both:- 

**(1) highly accurate and (2) capable of being executed in real-time.**

## Understanding deep learning face recognition embeddings

Instead, of trying to output a single label (or even the coordinates/bounding box of objects in an image), we are instead outputting a real-valued feature vector.

For the dlib facial recognition network, the output feature vector is 128-d (i.e., a list of 128 real-valued numbers) that is used to quantify the face. Training the network is done using triplets: 

![face_recognition_opencv_triplet](https://user-images.githubusercontent.com/49313619/86593895-b2eab980-bfb3-11ea-96a1-97f0a2528c19.jpg)

From there, the general idea is that we’ll tweak the weights of our neural network so that the 128-d measurements of the two Will Ferrel will be closer to each other and farther from the measurements for Chad Smith.

The network architecture for face recognition is based on ResNet-34 from the Deep Residual Learning for Image Recognition paper by He et al., but with fewer layers and the number of filters reduced by half.Note: For the following installs, ensure you are in a Python virtual environment if you’re using one. I highly recommend virtual environments for isolating your projects — it is a Python best practice. If you’ve followed my OpenCV install guides (and installed virtualenv  + virtualenvwrapper ) then you can use the workon  command prior to installing dlib  and face_recognition

The network itself was trained by Davis King on a dataset of ~3 million images. On the Labeled Faces in the Wild (LFW) dataset the network compares to other state-of-the-art methods, reaching 99.38% accuracy.

## Pre-requisites and steps are mentioned in the "CMD Commands.txt" file.

**Note: I would suggest you to istall dlib using GPU support if you have a GPU enabled system as it will make the training process faster. You can follow the steps mentioned in the link below to install Cuda and CudaDNN for your Nvidia graphic driver which will help you enable GPU support.**

*Note: For the following installs, ensure you are in a Python virtual environment if you’re using one. I highly recommend virtual environments for isolating your projects — it is a Python best practice. If you’ve followed my OpenCV install guides (and installed virtualenv  + virtualenvwrapper ) then you can use the workon  command prior to installing dlib  and face_recognition*

## Test Image for Face Recognition in an image

![test](https://user-images.githubusercontent.com/49313619/86594808-4c669b00-bfb5-11ea-99cc-beefa932ca66.jpg)

## Face Recognition example in an image

![Screenshot (14)](https://user-images.githubusercontent.com/49313619/86594937-89329200-bfb5-11ea-80f8-5f16df6ff862.png)

## Face Recognition example using Video cam live stream

![Screenshot (17)](https://user-images.githubusercontent.com/49313619/86595207-0100bc80-bfb6-11ea-9b71-33178ce7413b.png)





