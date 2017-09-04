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

* `lane_lines.ipynb`:  Jupyter notebook contains the project code. 
* `writeup_report.md`: The project writeup can be found in.

Folders:
* `camera_cal`: Images for camera calibration
* `test_images`: Images for testing your pipeline on single frames.  
* `test_images_output`: Contains intermediate images from my processing pipeling, using input images from the `test_images` folder.
* `test_videos`: Input videos for the project.
* `test_videos_output`: Output videos using input videos from the `test_videos` folder.

The folder `test_images_output` contains the following:
* Input image (01_image_in)
* Undistorted image (02_undistorted_image)
* Combined threshold - binary image (03_combined)
* Plotted polygon of ROI onto original image (04_plot_poly_roi)
* Grayscale image of ROI only (05_image_roi_binary)
* Polygon for imagepoints/objectspoints on image (06_image_roi_poly1)
* Warped color image (07_plot_warped_color)
* Warped grayscale image (08_warped_binary)
* Polygon in original image (09_result)
* Polygon onto warped image + windows (09_test)
* Final result (10_result_text)

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
