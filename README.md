# DietService-ObjectDetection
#### Alpaco Object Detection mini Project
### Team
* 김현나, 손보영, 이종헌, 전영욱, 허 권
<br><br>
## Project
* Object Detection for Diet Service
<br><br>
## Introduction
* 현재 자기관리가 하나의 트랜드처럼 자리잡고있음

* 운동만큼 식단의 중요성이 부각됨

* 핸드폰 카메라 하나만으로 식단관리가 가능한 서비스가 있으면 어떨까 하는 생각에 시작한 프로젝트

* Object Detection을 통해 음식을 인식하고 칼로리와 영양정보를 제공
<br><br>
## Models and Data
* YOLO V4

* 12,000개의 한식, 일식, 양식 이미지 데이터

* 총 100개의 class

* multiple food-item, single food-item으로 구성
<br><br>
## Envs and Requirements
* Google Colab, VScode

* Tensorflow, Glob, Shutil, Pillow, OpenCV, Darknet
<br><br>
## Progress
* 데이터셋 구축

* 데이터셋 정제   
이미지 한 폴더에 모으기 - 각각의 클래스 폴더별로 이미지가 나뉘어있음   
이미지 사이즈 정규화 - bbox 좌표 정규화   

* Train & Inference
<br><br>
## Reference
* https://arxiv.org/abs/2004.10934
* https://github.com/AlexeyAB/darknet
* https://opencv.org/
* https://pillow.readthedocs.io/en/stable/
* https://www.tensorflow.org/?hl=ko
