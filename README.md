# GestureDetectionPorject
This is a Tensorflow Object Detection Project inspired by Nicholas Renotte.

The goal of this project is detecting gesture in real time in order to collect customers feedback.

For gestures, three states: "Thumps Up", "Thumps Down", "Okay" will be detected.

![image](https://user-images.githubusercontent.com/85855794/126082140-5e2c6547-4fea-4d27-a221-1bfa1969d6dc.png)


## Method
The deep learning pre-trained model I used in this project is SSD MobileNet v2 320x320 from TensorFlow 2 Detection Model Zoo.

And I used OpenCV to connect to webcame and do real time detection.

For labeling, I used pyqt5 to label a selected region.

## Result
The following is the result of loss and evaluation matrix from TensorBoard.
![image](https://user-images.githubusercontent.com/85855794/126082173-62cadbfb-47cf-4e28-80f4-944daa26bbdb.png)
![image](https://user-images.githubusercontent.com/85855794/126082203-769850e6-3ade-415e-93c0-c6901fdc38fc.png)

## Conclusion
This model still can be improved by collecting more images and adding more training steps. 

Also, I found that if the gestures in the image we collected are close to our face, we'll detect the gestures only when they are close to face. That is to say that we might use that relation to do some interactive gesture detection in the future.
