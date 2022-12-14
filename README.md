# VOLUME & BRIGHTNESS CONTROL


## MediaPipe offers cross-platform, customizable ML solutions for live and streaming media.
MediaPipe is a Framework for building machine learning pipelines for processing time-series data like video, audio, etc. This cross-platform Framework works in Desktop/Server, Android, iOS, and embedded devices like Raspberry Pi and Jetson Nano.


## Hand Landmark Model
- Hand landmark model performs precise keypoint localization of 21 3D hand-knuckle coordinates inside the detected hand regions via regression, that is direct coordinate prediction.

![download](https://user-images.githubusercontent.com/67835489/201744385-9a5da11c-4cde-4e52-975f-f8a1c3e19b40.png)

## libraries you need 
- cv2
- mediapipe 
- pynput
- screen_brightness_control

## How it works
- I have divided the screen into two halves. When the hand is on the right side, we control the lighting. The left side controls the sound.
