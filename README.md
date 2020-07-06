# Face-Recognition-Model-using-Deep-Learning
Face Recognition Model using Deep Learning technique know as Deep metric Learning

Perform face recognition in both images and video cam streams using:

**-OpenCV**

**-dlib**

**-Python**

**-Deep learning**

The deep learning-based facial embeddings are both:- 

**(1) highly accurate and (2) capable of being executed in real-time.**

## Understanding deep learning face recognition embeddings

Instead, of trying to output a single label (or even the coordinates/bounding box of objects in an image), we are instead outputting a real-valued feature vector.

For the dlib facial recognition network, the output feature vector is 128-d (i.e., a list of 128 real-valued numbers) that is used to quantify the face. Training the network is done using triplets: 
![face_recognition_opencv_triplet](https://user-images.githubusercontent.com/49313619/86593895-b2eab980-bfb3-11ea-96a1-97f0a2528c19.jpg)

From there, the general idea is that we’ll tweak the weights of our neural network so that the 128-d measurements of the two Will Ferrel will be closer to each other and farther from the measurements for Chad Smith.

The network architecture for face recognition is based on ResNet-34 from the Deep Residual Learning for Image Recognition paper by He et al., but with fewer layers and the number of filters reduced by half.

The network itself was trained by Davis King on a dataset of ~3 million images. On the Labeled Faces in the Wild (LFW) dataset the network compares to other state-of-the-art methods, reaching 99.38% accuracy.







