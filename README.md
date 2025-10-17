# Features #

1. Face detection and recognition (images and videos)
1.Outline identification
1. Avatar synthesis (putting hats on people)
1. Digital makeup (applying lipstick, eyebrows, eyes, etc.)
1.Gender recognition
1. Expression recognition (seven emotions: anger, disgust, fear, happiness, sadness, surprise, and calmness)
2. Video object extraction
3. Image restoration (can be used for watermark removal)
4. Automatic image colorization
3. Eye tracking (to be improved)
3. Face swapping (to be improved)

**See feature preview↓↓↓**

# Development Environment #

- Windows 10 (x64)
-Python 3.6.4
- OpenCV 3.4.1
- Dlib 19.8.1
- face_recognition 1.2.2
- keras 2.1.6
- tensorflow 1.8.0
- Tesseract OCR 4.0.0-beta.1

# Tutorial #

[OpenCV Environment Setup](doc/settingup.md)

[Tesseract OCR Text Recognition (doc/tesseractOCR.md)

Face Detection in Images (OpenCV Version) (doc/detectionOpenCV.md)

Face Detection in Images (Dlib Version) (doc/detectionDlib.md)

Face Detection in Videos (OpenCV Version) (doc/videoOpenCV.md)

Face Detection in Videos (Dlib Version) (doc/videoDlib.md)

Face Outline Drawing (doc/faceRecognitionOutline.md)

Digital Makeup (doc/faceRecognitionMakeup.md)

Face Recognition in Videos (doc/faceRecognition.md)

Avatar Effect Composition (doc/compose.md)

Gender Recognition (doc/gender.md)

Expression Recognition (doc/emotion.md)

# Other Tutorials #

[Ubuntu [Replace apt-get and pip sources](doc/ubuntuChange.md)

[Replace pip/pip3 domestic sources - Windows version](doc/pipChange.md)

[Add Chinese to OpenCV](doc/chinese.md)

# Feature Preview #

**Drawing facial outline**

<img src="https://raw.githubusercontent.com/vipstone/faceai/master/res/face_recognition-outline.png" width = "250" height = "300" alt="Drawing facial outline" />

----------

**Identifying 68 key points on the face**

<img src="https://raw.githubusercontent.com/vipstone/faceai/master/res/dlib68.png" width = "230" height = "300" alt="Identifying 68 key points on the face" />

----------

**Avatar special effects synthesis**

<img src="https://raw.githubusercontent.com/vipstone/faceai/master/res/compose.png" width = "200" height = "300" alt="Avatar Effect Composition" />

----------

**Gender Recognition**

<img src="https://raw.githubusercontent.com/vipstone/faceai/master/res/gender.png" width = "430" height = "220" alt="Gender Recognition" />

----------

**Emotion Recognition**

<img src="https://raw.githubusercontent.com/vipstone/faceai/master/res/emotion.png" width = "250" height = "300" alt="Emotion Recognition" />

----------

**Digital Makeup**

<img src="https://raw.githubusercontent.com/vipstone/faceai/master/res/faceRecognitionMakeup-1.png" width = "450" ​​height = "300" alt="Video Face Recognition" />

----------

**Video Face Detection**

![](https://raw.githubusercontent.com/vipstone/faceai/master/res/video-jiance.gif)

----------

**Video Face Recognition**

![](https://raw.githubusercontent.com/vipstone/faceai/master/res/faceRecognition.gif)

----------

**Video Face Recognition**

![](http://icdn.apigo.cn/opencv-hsv.gif)

----------

**Image Inpainting**

![](http://icdn.apigo.cn/inpaint.png?2)

----------

**Image Automatic Colorization**

![](http://icdn.apigo.cn/colorize-faceai.png)

----------

# Technical Solution #

Technical Implementation Solution Introduction

Face Recognition: OpenCV / Dlib

Face Detection: face_recognition

Gender Recognition: Keras + TensorFlow

Text Recognition: Tesseract OCR

### TODO ###

Face Swapping — To Be Improved

Eye Movement Direction Detection — To Be Improved

Dlib Performance Optimization Solution

Dlib Model Training Method

Tesseract Model Training Method
