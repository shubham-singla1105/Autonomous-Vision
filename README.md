# Lane and Vehicle Detection System

### Introduction

This project aims to develop a Lane and Vehicle Detection pipeline that replicates the functionality of Lane Departure Warning (LDW) systems used in autonomous vehicles. The system leverages computer vision and deep learning techniques for accurate lane and vehicle detection.

### Prerequisites

The implementation is based on Python 3.6 and utilizes OpenCV for lane detection and the TensorFlow Object Detection API for vehicle detection.

### Requirements:

Python 3.6

OpenCV

TensorFlow Object Detection API

A dataset of videos for testing

For vehicle detection, the TensorFlow Object Detection API must be downloaded, and the relevant Python script should be executed along with the video dataset.

Implementation Pipeline

### The following steps outline the lane detection pipeline:

Step 1: Color Thresholding and Noise Reduction

The system applies color masks to detect lane markings based on yellow and white color segmentation.

Step 2: Region of Interest (ROI) Extraction and Edge Detection

A region of interest (ROI) is extracted, focusing on the lower half of the image where lane markings are expected. The combined color masks are then processed using an edge detection algorithm.

### Edge Detection:


Step 3: Hough Transform and RANSAC for Lane Detection

To enhance the robustness of lane detection, the system applies the Hough Transform, followed by RANSAC (RANdom SAmple Consensus) for filtering and improving accuracy.

Step 4: Integration with TensorFlow Object Detection API

The lane detection module is integrated with the TensorFlow Object Detection API for vehicle detection. This step enables real-time detection of both lanes and vehicles.

Final Lane and Vehicle Detection Output:https://github.com/shubham-singla1105/Autonomous-Vision/blob/main/Advanced-Lane-and-Vehicle-Detection-master/project_video_out.mp4


### Results

The final implementation successfully detects lanes and vehicles in real-time. A demonstration of the system can be viewed in the following video: Lane and Vehicle Detection Video

## Author

Shubham Singla- [GitHub Profile](https://github.com/shubham-singla1105)

### Acknowledgments

The lane detection video dataset was sourced from the Udacity Self-Driving Car Course for development and testing purposes.
