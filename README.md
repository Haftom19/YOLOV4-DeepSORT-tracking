
# People Tracking in crowded location using Multiple Object Tracking (MOT)

This project is focused on Multiple Object Tracking (MOT) which is an important topic in the field of computer vision. It can be used in various advanced technology applications such as autonomous driving systems, traffic monitoring, and analyzing people in different fields such as sports players. The project applied an MOT algorithm for tracking people in crowded areas with the help of a detection system. The model uses the tracking-by-detection (DBT) strategy and uses the YOLOv4 algorithm for detection and the DeepSORT algorithm for tracking. A Kalman filter is used to predict the locations of existing tracks in the current frame from the previous frame.The YOLOv4 detection algorithm is used for evaluation on the MOT20 dataset and achieved a 97.7% mAP value for the detection system.




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
The methods employed for object detection and tracking involved various techniques, including different conducted methods and experiments on training datasets. The initial step focused on introducing the dataset section, 
outlining how the dataset was organized for training the detection system. Subsequently, implementations, evaluations of metrics, and discussions were conducted to assess the effectiveness of the employed methods.

MOTChallenge, offering meticulously annotated datasets and well-defined metrics for evaluating tracking algorithms and pedestrian detectors, served as chosen dataset for training my model. 
Trained a YOLOv4 and YOLOv4-tiny model with the Darknet-53 backbone specifically on MOT20 training sequences. Emphasized aligning the model's data format with MOT20 for effective learning. 
The labeling process highlighted key features crucial for pattern analysis, enhancing target prediction.

The ground truth file of MOT20 benchmark has the file format as shown below.

`<frame>`, `<id>`, `<bbleft>`, `<bbtop>`, `<width>`, `<height>`, `<conf>`, `<x>`, `<y>`, `<z>`


| Field   | Description    |
| ------- | -------------- |
| `<frame>`  | frame number|
| `<id>`     | Identity number    |
| `<bbleft>` | Bounding box left|
| `<bbtop>`  | Bounding box right |
| `<width>`  | Bounding box width |
| `<height>` | Bounding box heightd|
| `<conf>`   | Confidence score  |
| `<x>`      | class    |
| `<y>`      | visibility   |
| `<z>`      |     |


The YOLO format consists of object class, object coordinates,height, and width as the following format

`<object-class>`, `<x>`, `<y>`, `<width>`, `<height>`









### Prerequisites





## Built With

* [Google colab](https://colab.research.google.com/) - allows you to write and execute Python in your browser

## Authors

* **Hafom Abrha Solomon** - [Haftom19](https://github.com/Haftom19)

## License

This project is licensed under the WUT license 

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc






















![⭐_People_tracking_in_crowded_locations_using_multiple_object_Tracking⭐](https://user-images.githubusercontent.com/81158076/204558252-92f35b04-3096-4b44-bbb5-9b2f3c5f168e.png)

YOLO4 training
<a href="https://colab.research.google.com/drive/1NNCwbsB_yZbIxn03OWAIpG_YuubEqicd?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

YOLOV4-DeepSORT tracking
<a href="https://colab.research.google.com/drive/1gKViQZSB-ECwkFQbF4VPIaO_kGf-rBge?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

YOLOv4-tiny training
<a href="https://colab.research.google.com/drive/1w4V-7RYrDETmNGVjd891x92fPsjldiw1?usp=share_link">
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
