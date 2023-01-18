
# People Tracking in crowded location using Multiple Object Tracking (MOT)

This project is focused on Multiple Object Tracking (MOT) which is an important topic in the field of computer vision. It can be used in various advanced technology applications such as autonomous driving systems, traffic monitoring, and analyzing people in different fields such as sports players. The project applied an MOT algorithm for tracking people in crowded areas with the help of a detection system. The model uses the tracking-by-detection (DBT) strategy and uses the YOLOv4 algorithm for detection and the DeepSORT algorithm for tracking. A Kalman filter is used to predict the locations of existing tracks in the current frame from the previous frame. To improve the data association of DeepSORT, a set of new object tracking data association cost matrices based on intersection over union and bounding box metrics is proposed. The YOLOv4 detection algorithm is used for evaluation on the MOT20 dataset and achieved a 97.7% mAP value for the detection system.

## Table of contents
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Running the tests](#running-the-tests)
- [Deployment](#deployment)
- [Built With](#built-with)
- [Authors](#authors)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

























![⭐_People_tracking_in_crowded_locations_using_multiple_object_Tracking⭐](https://user-images.githubusercontent.com/81158076/204558252-92f35b04-3096-4b44-bbb5-9b2f3c5f168e.png)

YOLO4 training
<a href="https://colab.research.google.com/drive/1NNCwbsB_yZbIxn03OWAIpG_YuubEqicd?authuser=4#">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

YOLOV4-DeepSORT tracking
<a href="https://colab.research.google.com/drive/1gKViQZSB-ECwkFQbF4VPIaO_kGf-rBge?authuser=6">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

YOLOv4-tiny training
<a href="https://colab.research.google.com/drive/1w4V-7RYrDETmNGVjd891x92fPsjldiw1?authuser=3">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>


![✔️_Detection-YOLOv4](https://user-images.githubusercontent.com/81158076/204559586-fd8b90f8-3865-432b-8d75-a5b92bc16ee0.png)

![✔️_Tracking_-DeepSORT (1)](https://user-images.githubusercontent.com/81158076/204559605-d69606b6-c6af-420c-88d4-cfc0ebcf7533.png)

# <h2> Detection Result video

https://user-images.githubusercontent.com/81158076/204257899-aaed8c45-7ccc-427f-a0b9-c171f795b3c1.mp4


# <h2> Tracking Result video


https://user-images.githubusercontent.com/81158076/204257874-506948b2-57e3-4d12-b3b1-c63b951e89f4.mp4

  
<p align="right">

 ![ezgif-4-aeeb506440 (1)](https://user-images.githubusercontent.com/81158076/204807348-196d23a8-64b8-4c0b-845c-d292bc7d1d1f.gif)

  
</p>
