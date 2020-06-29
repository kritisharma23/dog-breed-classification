# Dog-Breed Classifier - CNN Project
This project is a part of **Udacity Deep Learning Nanodegree** Program.

## Project Overview

The aim of this project is to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. The code accepts any user-supplied image as input and performs the following tasks:
 1. If a dog is detected in the image, the algorithm will return the predicted breed.
 2. If supplied an image of a human, the code will identify the resembling dog breed.
 
 **Convolutional Neural Network** models are used to perform the above classifications. 
 
 ## Technologies Used
 
 1. Python (version 3.6.3)
 2. Pytorch (version 0.4.0)
 3. Jupyter Notebook
 
 ## Steps Involved
 
  1. **Detect Human Faces:** OpenCV's implementation of [Haar feature-based cascade classifiers](https://docs.opencv.org/trunk/d7/d8b/tutorial_py_face_detection.html) is used to detect human faces in images.
  
  2. **Detect Dogs:** Pre-trained [VGG-16](https://pytorch.org/docs/master/torchvision/models.html) model is used to detect dogs.
  
  3. **Create a CNN to Classify Dog Breeds (from Scratch):** The CNN is built from scratch to perform the above classification. 
  
  4. **Create a CNN to Classify Dog Breeds (using Transfer Learning):** Pre-trained [VGG-19](https://pytorch.org/docs/master/torchvision/models.html) model is used for transfer learning. 



