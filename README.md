# Real-Time-Object-Detection-YOLO

This project implements a real time object detection via video, webcam and image detection using YOLO algorithm. YOLO is a object detection algorithm which stand for You Only Look Once. I've implemented the algorithm from scratch in Python using pre-trained weights. YOLOv3 was published in research paper: YOLOv3: An Incremental Improvement: Joseph Redmon, Ali Farhadi It's originally implemented in YOLOv3.

COCO dataset is used for training.

Real time detection can be use via command prompt or GUI.

A USA Real-Time Road Detection

A UK Real-Time Road Detection

A Real-Time Webcam Detection

Yolo is a deep learning algorythm which came out on may 2016 and it became quickly so popular because it’s so fast compared with the previous deep learning algorythm. With yolo we can detect real time objects at a relatively high speed. With a GPU we would be able to process over 45 frames/second while with a CPU around a frame per second.

OpenCV dnn module supports running inference on pre-trained deep learning models from popular frameworks like Caffe, Torch and TensorFlow.

Requirement
OpenCV 4.2.0
Python 3.6
Quick start
Download official yolov3.weights and place it under a folder called weight.
Download official yolov3-tiny.weights and place it under a folder called weight.
Download yolov3.cfg and place it under a folder called cfg.
Download yolov3-tiny.cfg and place it under a folder called cfg.
Dependencies
opencv
numpy
Install dependencies
pip install numpy opencv-python

How to use?
Clone the repository
git clone https://github.com/muhammadshiraz/YOLO-Real-Time-Object-Detection.git

Move to the directory
cd YOLO-Real-Time-Object-Detection

To view the UK Real-Time Road Detection
python real_time_yolo_detector1.py

To view the USA Real-Time Road Detection
python real_time_yolo_detector2.py

To use in real-time on webcam
python real_time_yolo_webcam.py

Graphical User Interface:
A USA Real-Time Road Detection


A UK Real-Time Road Detection


A Real-Time Webcam Detection
