# Vehicle Detection
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

Objective : This project aims to recognize cars in a video and track them.

The Project
---

The goals / steps of this project are the following:

* Perform a Histogram of Oriented Gradients (HOG) feature extraction on a labeled training set of images and train a classifier Linear SVM classifier
* Optionally, you can also apply a color transform and append binned color features, as well as histograms of color, to your HOG feature vector. 
* Note: for those first two steps don't forget to normalize your features and randomize a selection for training and testing.
* Implement a sliding-window technique and use your trained classifier to search for vehicles in images.
* Run your pipeline on a video stream (start with the test_video.mp4 and later implement on full project_video.mp4) and create a heat map of recurring detections frame by frame to reject outliers and follow detected vehicles.
* Estimate a bounding box for vehicles detected.

Here are links to the labeled data for [vehicle](https://s3.amazonaws.com/udacity-sdc/Vehicle_Tracking/vehicles.zip) and [non-vehicle](https://s3.amazonaws.com/udacity-sdc/Vehicle_Tracking/non-vehicles.zip) examples to train your classifier.  These example images come from a combination of the [GTI vehicle image database](http://www.gti.ssr.upm.es/data/Vehicle_database.html), the [KITTI vision benchmark suite](http://www.cvlibs.net/datasets/kitti/), and examples extracted from the project video itself.   You are welcome and encouraged to take advantage of the recently released [Udacity labeled dataset](https://github.com/udacity/self-driving-car/tree/master/annotations) to augment your training data.  

# Improvements for next version:
---
1) False positives - Hard mining
2) Stable bounding boxes - fix size bounding box
3) Explore YOLO, SSD, Unet, and Haar Cascade classifiers.


Resources for improvement:

GENERAL PAPERS ON VEHICLE DETECTION
http://cmp.felk.cvut.cz/~vojirtom/publications/itsc2012.pdf
http://ijiset.com/vol2/v2s7/IJISET_V2_I6_08.pdf
http://old.cescg.org/CESCG-2014/papers/Sochor-Fully_Automated_Real-Time_Vehicles_Detection_and_Tracking_with_Lanes_Analysis.pdf

DEALING WITH CURVED LANE LINES
http://refbase.cvc.uab.es/files/LSC2010.pdf
http://www.vision.caltech.edu/malaa/publications/aly08realtime.pdf
http://campar.in.tum.de/pub/gackstatter2010amaa/gackstatter2010amaa.pdf

LITTLE EXPOSURE DETECTIONS
http://car.nuigalway.ie/documents/romalley_ieeeitsrearlamp.pdf

VEHICLE DETECTION IN AERIAL IMAGES BASED ON REGION
Convolutional Neural Networks and Hard Negative Example Mining.






