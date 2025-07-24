# Real-Time-Object-Detection-YOLO

This project implements a real-time object detection system using the YOLOv3 (You Only Look Once) algorithm with OpenCV and pre-trained weights on the COCO dataset. YOLOv3 is a powerful, single-shot deep learning model capable of detecting objects with high accuracy and speed. It processes frames in real time and detects multiple object classes simultaneously.

🔧 Features:
📹 Real-time detection from webcam and video input using YOLOv3

🖼️ Supports image, video, and live webcam detection modes

🧠 Uses YOLOv3 pre-trained weights on the COCO dataset (80+ object classes)

🏎️ Fast detection performance using OpenCV’s dnn module

🗺️ Road detection scenes for both UK and USA style input videos

🎛️ Modular and customizable code structure for extending to other YOLO versions (e.g., YOLOv4, v5)

🛠 Tech Stack:
Python 3.6+

OpenCV (4.2.0+)

NumPy

YOLOv3 config and weights

📂 How to Use:
Clone the repo:


git clone https://github.com/Pulishekhar/Real-Time-Object-Detection-YOLO-.git
cd Real-Time-Object-Detection-YOLO-
Install dependencies:


pip install opencv-python numpy
Download the following files and place them accordingly:

yolov3.cfg → inside /cfg folder

yolov3.weights → inside /weights folder

coco.names → inside /data folder

Run detection scripts:

For UK Road Detection:


python real_time_yolo_detector1.py
For USA Road Detection:


python real_time_yolo_detector2.py
For Webcam-based Detection:


python real_time_yolo_webcam.py
📊 Output:
Real-time bounding boxes with class labels (e.g., car, person, traffic light)

Optional confidence threshold display

Smooth and fast inference pipeline (real-time FPS achievable on CPU/GPU)

📌 Use Cases:
Road traffic monitoring

Autonomous vehicle simulations

Real-time surveillance and object tracking

Smart security systems


