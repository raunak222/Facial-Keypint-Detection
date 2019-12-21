# Facial-Keypint-Detection
This is a repository of my project facial keypoints detection. This is the first project of my Computer Vision  Nanodegree
![alt text](https://github.com/raunak222/Facial-Keypint-Detection/blob/master/key_pts_example.png)

## Introduction:
- Facial Key Points (FKPs) detection is an important and
challenging problem in the field of computer vision, which
involves detecting FKPs like centers and corners of eyes,
nose tip, etc. The problem is to predict the (x, y) realvalued co-ordinates in the space of image pixels of the FKPs
for a given face image. It finds its application in tracking
faces in images and videos, analysis of facial expressions,
detection of dysmorphic facial signs for medical diagnosis,
face recognition, etc.

##  Motivation/Purpose: 
- Main Purpose of this project is to detect facial keypoint from a given image dataset. So first we define the CNN Architecture for this 
### CNN Architecture
- Convolutional layers
- Maxpooling layers
- Fully-connected layers
in model.py file
Then We detect the face using Haar Cascade classifier after detecting frontial faces we pass these detected faces to trained model

##  How to Use 
- Go through instruction [here](https://github.com/raunak222/Facial-Keypint-Detection/blob/master/Instruction.txt)

##  Some Visualization
 ![alt text](https://github.com/raunak222/Facial-Keypint-Detection/blob/master/haar_cascade_ex.png)
## Input Image
![alt text](https://github.com/raunak222/Facial-Keypint-Detection/blob/master/download%20(3).png)
### Output Image
![alt text](https://github.com/raunak222/Facial-Keypint-Detection/blob/master/detect.png)
### Output Image
![alt text](https://github.com/raunak222/Facial-Keypint-Detection/blob/master/download%20(1).png)
## Using Pysyft
 - First we perform normal style tranfer using pytorch then send the output to another user on same network using Pysyft, we also demonstrate that this can be send with encryption.

- If another user gets the access to the data then we make sure to retrieve the data from user.
## Developer 
  Raunak Sarada  
  - [Github](https://github.com/raunak222) 
  - [linkedin](https://www.linkedin.com/in/raunak-sarada)
## Resources 
- https://github.com/udacity/P1_Facial_Keypoints
- https://blog.openmined.org
- https://arxiv.org/pdf/1710.00977.pdf

## Citation
- Udacity Computer Vision Nanodegree
