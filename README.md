# GestureDetectionPorject
This is a Tensorflow Object Detection Project inspired by Nicholas Renotte.

The goal of this project is detecting gesture in real time in order to collect customers feedback.

For gestures, three states: "Thumps Up", "Thumps Down", "Okay" will be detected.

## Method
The deep learning pre-trained model I used in this project is SSD MobileNet v2 320x320 from TensorFlow 2 Detection Model Zoo.

And I used OpenCV to connect to webcame and do real time detection.

For labeling, I used pyqt5 to label a selected region.

