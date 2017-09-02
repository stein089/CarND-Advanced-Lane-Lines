# Advanced Lane Finding Project

[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

Overview
---
This repository contains my implementation of the Advanced Lane Finding Project (Term 1 - Project 4), which is part of the Udacity Self Driving Car NanoDegree .

### Dependencies
This lab requires:

* [CarND Term1 Starter Kit](https://github.com/udacity/CarND-Term1-Starter-Kit)

The lab enviroment can be created with CarND Term1 Starter Kit. 
Click [here](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/README.md) for the details.

### Files

The jupyter notebook `lane_lines.ipynb` contains the project code. 
The project writeup can be found in `writeup_report.md`.

The images for camera calibration are stored in the folder called `camera_cal`.  
The images in `test_images` are for testing your pipeline on single frames.  
The folder `test_images_output` contains intermediate images from my processing pipeling, using input images from the `test_images` folder.
The folder `test_videos_output` contains output videos using input videos from the `test_videos` folder.

The video called `project_video.mp4` is the video your pipeline should work well on.  
The `challenge_video.mp4` video is an extra (and optional) challenge for you if you want to test your pipeline under somewhat trickier conditions.  
The `harder_challenge.mp4` video is another optional challenge and is brutal!


### The Project

The goals / steps of this project were the following:

* Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
* Apply a distortion correction to raw images.
* Use color transforms, gradients, etc., to create a thresholded binary image.
* Apply a perspective transform to rectify binary image ("birds-eye view").
* Detect lane pixels and fit to find the lane boundary.
* Determine the curvature of the lane and vehicle position with respect to center.
* Warp the detected lane boundaries back onto the original image.
* Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.
