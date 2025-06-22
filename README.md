🎯 Real-Time Face Detection using Viola-Jones Algorithm
This project demonstrates real-time face detection using the Viola-Jones algorithm, implemented with OpenCV. The algorithm is fast, efficient, and ideal for detecting frontal human faces in a webcam feed.

🧠 About Viola-Jones Algorithm
The Viola-Jones object detection framework is based on:

Haar-like features for detecting patterns in images

Integral images for fast computation

AdaBoost for feature selection and building a strong classifier

Cascade classifier for speeding up the detection by filtering non-face regions quickly

📸 Real-Time Face Detection
The webcam is used to capture video frames, which are processed in real-time to:

Convert frames to grayscale

Detect faces using a Haar Cascade classifier

Draw rectangles around detected faces

🧰 Technologies Used
Python

OpenCV

Haar Cascade Classifier

🚀 Getting Started
📦 Installation
bash
Copy
Edit
pip install opencv-python
