# Social Distancing Detector [![](https://img.shields.io/badge/Anshu-Jha-brightgreen.svg?colorB=ff0000)](https://www.linkedin.com/in/anshu-jha-835723194/)
An AI Model to Help Customers Monitor Social Distancing in the Workplace.

### Sourcerer 

In the fight against the coronavirus, social distancing has proven to be a very effective measure to slow down the spread of the disease. While millions of people are staying at home to help flatten the curve, many customers in the manufacturing and pharmaceutical industries are still having to go to work everyday to make sure our basic needs are met.

To help ensure social distancing protocol in their workplace, I have developed an AI-enabled social distancing detection model that can detect if people are keeping a safe distance from each other by analyzing real time video streams from the camera.

The demos below will help to visually explain the approach that consists of three main steps:

1. Detect the humans in the frame with yolov3 convolutional neural network.
2. Calculate the distance between all the instances of humans detected in the frame.
3. Classify the determined distances as 'Alert' or 'Ok' for social distancing.


### Output (Video)
This demo video is performed on one of the most crowded area in Delhi.

![This demo video is performed on one of the most crowded area in Delhi](https://github.com/dominator-220/Social-Distancing-Detector/blob/main/videos/output.gif)


### Requirements:

1. Numpy
2. OpenCV
3. Math

Download yolov3.weights for COCO dataset from this link and add it to your repo, [click here](https://pjreddie.com/darknet/yolo/)

### Installation of Model:

* To deploy algorithm on images, python SDD_Image.py
* To deploy algorithm on videos, python SDD_Video.py
* To deploy algorithm on live streaming webcam, python SDD_Camera.py


Reference: https://landing.ai/landing-ai-creates-an-ai-tool-to-help-customers-monitor-social-distancing-in-the-workplace/
