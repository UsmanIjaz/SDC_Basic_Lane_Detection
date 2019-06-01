# **Finding Lane Lines on the Road** 
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

<img src="examples/laneLines_thirdPass.jpg" width="480" alt="Combined Image" />

Overview
---

When we drive, we use our eyes to decide where to go.  The lines on the road that show us where the lanes are act as our constant reference for where to steer the vehicle.  Naturally, one of the first things we would like to do in developing a self-driving car is to automatically detect lane lines using an algorithm.

In this project we will detect lane lines in images using Python and OpenCV.  OpenCV means "Open-Source Computer Vision", which is a package that has many useful tools for analyzing images.  

The code file is called Basic_Lane_Detection.ipynb. 

Here is the output for the test images.
![SolidWhiteCurve](test_images_output/final_solidWhiteCurve.jpg)
![SolidWhiteRight](test_images_output/final_solidWhiteRight.jpg)
![SolidYellowCurve](test_images_output/final_solidYellowCurve.jpg)
![SolidYellowCurve2](test_images_output/final_solidYellowCurve2.jpg)
![SolidYellowLeft](test_images_output/final_solidYellowLeft.jpg)
![WhiteCarLaneSwitch](test_images_output/final_whiteCarLaneSwitch.jpg)

Here is the output for the test videos.
![solidWhiteRight](test_videos_output/solidWhiteRight.mp4)
![solidYellowLeft](test_videos_output/solidYellowLeft.mp4)
