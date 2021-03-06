## Vehicle Detection

The goals / steps of this project are the following:

* Perform a Histogram of Oriented Gradients (HOG) feature extraction on a labeled training set of images and train a classifier Linear SVM classifier
* Apply a color transform and append binned color features, as well as histograms of color, to your HOG feature vector. 
* for those first two steps normalize your features and randomize a selection for training and testing.
* Implement a sliding-window technique and use your trained classifier to search for vehicles in images.
* Run the pipeline on a video stream (start with the test_video.mp4 and later implement on full project_video.mp4) and create a heat map of recurring detections frame by frame to reject outliers and follow detected vehicles.
* Estimate a bounding box for vehicles detected.


## Dependencies

* Python 3.10
* Numpy
* OpenCV-Python
* Moviepy
* Matplotlib
* Glob
* Random
* Time
* Pickle


## Note

Data file -which contains the images for visualizing train images- must be downloaded from here : https://drive.google.com/file/d/1gIyMqxqxClA7os5CgK3VqzigP58TBqjH/view
