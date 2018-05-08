# 功能 #

1. 人脸检测、识别（图片、视频）
1. 轮廓标识
1. 头像合成（给人戴帽子）
1. 数字化妆（画口红、眉毛、眼睛等）
1. 性别识别
1. 表情识别（生气、厌恶、恐惧、开心、难过、惊喜、平静等七种情绪）

**查看功能预览↓↓↓**

# 开发环境 #

- Windows 10（x64）
- Python 3.6.4
- OpenCV 3.4.1
- Dlib 19.8.1
- face_recognition 1.2.2
- keras 2.1.6
- tensorflow 1.8.0
- Tesseract OCR 4.0.0-beta.1


# 教程文档 #

[OpenCV环境搭建](doc/settingup.md)

[Tesseract OCR文字识别](doc/tesseractOCR.md)

[图片人脸检测（OpenCV版）](doc/detectionOpenCV.md)

[图片人脸检测（Dlib版）](doc/detectionDlib.md)

[视频人脸检测（OpenCV版）](doc/videoOpenCV.md)

[视频人脸检测（Dlib版）](doc/videoDlib.md)

[脸部轮廓绘制](doc/faceRecognitionOutline.md)

[数字化妆](doc/faceRecognitionMakeup.md)

[视频人脸识别](doc/faceRecognition.md)

[头像特效合成](doc/compose.md)

[性别识别](doc/gender.md)

表情识别（生气、厌恶、恐惧、开心、难过、惊喜、平静等七种情绪）

# 相关文档 #

[pip/pip3更换国内源](doc/pipChange.md)

[OpenCV添加中文](doc/chinese.md)


# 功能预览 #

**绘制脸部轮廓**

<img src="https://raw.githubusercontent.com/vipstone/faceai/master/res/face_recognition-outline.png" width = "250" height = "300" alt="绘制脸部轮廓" />

----------

**人脸68个关键点标识**

<img src="https://raw.githubusercontent.com/vipstone/faceai/master/res/dlib68.png" width = "230" height = "300" alt="人脸68个关键点标识" />

----------

**头像特效合成**

<img src="https://raw.githubusercontent.com/vipstone/faceai/master/res/compose.png" width = "200" height = "300" alt="头像特效合成"  />

----------

**性别识别**

<img src="https://raw.githubusercontent.com/vipstone/faceai/master/res/gender.png" width = "430" height = "220" alt="性别识别"  />

----------

**表情识别**

<img src="https://raw.githubusercontent.com/vipstone/faceai/master/res/emotion.png" width = "250" height = "300" alt="表情识别"  />

----------

**数字化妆**

<img src="https://raw.githubusercontent.com/vipstone/faceai/master/res/faceRecognitionMakeup.png" width = "230" height = "300" alt="视频人脸识别"  />

----------

**视频人脸检测**

![](https://raw.githubusercontent.com/vipstone/faceai/master/res/video-jiance.gif)

----------

**视频人脸识别**

![](https://raw.githubusercontent.com/vipstone/faceai/master/res/faceRecognition.gif)


# 技术方案 #

技术实现方案介绍

	人脸识别：OpenCV / Dlib

	人脸检测：face_recognition
	
	性别识别：keras + tensorflow

	文字识别：Tesseract OCR


### TODO ###

眼睛移动方向检测

OpenCV + Tensorflow模型的人脸识别

Dlib性能优化方案

Dlib模型训练方法

Tesseract模型训练方法



