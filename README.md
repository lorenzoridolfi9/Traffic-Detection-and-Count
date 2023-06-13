# Traffic-Detection-and-Count 🚗 🚛

##  This repository contains Computer Vision project files. In particular, Yolov8 has been applied for object detection tasks, which can create models that recognize cars, trucks, and other objects on the highway and monitor traffic by counting units passing by at a certain point.

## Dataset 📊
The dataset used in the following project contains highway traffic images, and is divided into 3 parts:
- training set (70%) : 4702 model training frames
- validation set (20%) : 1358 frames of model validation
- testing set (10%) : 674 frames to test the model.

There are too many classes:
- car
- big bus
- big truck
- bus -l-
- bus -s-
- mid truck
- small bus
- small truck
- truck -l-
- truck -m-
- truck -s-
- truck -xl-

The data set was taken from Roboflow, which also annotated the classes for each frame.
You can download the dataset at the following [link](https://drive.google.com/drive/folders/1HaN7tSvvIt_7fmtwo0vxCRIS1TI7Qq1M?usp=sharing).

## Process of Analysis ⚙️
The computer vision application used yolov8 to perform object detection, ByteTrack for tracking, and the latest python library from Roboflow - Supervision for object counting.

## Results 📈
The end result is an .mp4 file that can detect different classes and count the number of objects entering and leaving a particular stretch of highway. 
This project can find several applications, such as monitoring certain particularly busy stretches, road safety, accident detection, parking management, and many others.

## Resources 💎
The .mp4 video used to do detection and counting is called __vehicle counting original__ and is available in my google drive at the following [link](https://drive.google.com/drive/folders/1MR0qf6GgHOVlcB59qc6Iw8vydiYvzB6n?usp=sharing), along with the code and the final .mp4 video obtained from the following project titled __vehicle counting final result__.

you can access the colab notebook containing the source code at the following [link](https://colab.research.google.com/drive/1UDXDHM_NAfgqgGEi2HjSY5h33yTHYiHf?usp=sharing).





