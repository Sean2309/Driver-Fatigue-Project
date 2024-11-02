# Driver-Fatigue-Project

## Introduction
Singapore is a densely populated city of over 6 million people to date. With the increasing number of vehicles on the road, the number of accidents is also increasing. According to the Singapore Police Force, accident fatalities has risen from 104 in 2022 to 131 in 2023 ([Link](https://www.police.gov.sg/-/media/D4435F72157942D3B323EE4A507D4CFB.ashx)).

The main cause of these accidents is driver fatigue. Fatigue is a state of mental and physical exhaustion that can lead to accidents. It is a common cause of accidents in Singapore. The aim of this project is to develop a system that can detect driver fatigue and alert the driver to prevent accidents.


## Problem Statement
The main problem is that drivers are not aware of their fatigue levels and continue to drive, which can lead to accidents. The aim of this project is to develop a system that can detect driver fatigue and alert the driver to prevent accidents.

Link: https://www.channelnewsasia.com/singapore/big-read-rising-traffic-accidents-road-culture-4328841

## Datasets
Majority of our datasets used will be from Kaggle. The possible datasets are as follows:
- https://www.kaggle.com/datasets/rakibuleceruet/drowsiness-prediction-dataset/data
- https://www.kaggle.com/datasets/dheerajperumandla/drowsiness-dataset/data
- https://www.kaggle.com/datasets/ismailnasri20/driver-drowsiness-dataset-ddd/data

## Acknowledgements
> **Ultralytics YOLOv8**  
> Author: Glenn Jocher, Ayush Chaurasia, Jing Qiu  
> Year: 2023  
> Version: 8.0.0  
> License: AGPL-3.0  
> URL: [https://github.com/ultralytics/ultralytics](https://github.com/ultralytics/ultralytics)  
> ORCID:  
> - [0000-0001-5950-6979](https://orcid.org/0000-0001-5950-6979) (Glenn Jocher)  
> - [0000-0002-7603-6750](https://orcid.org/0000-0002-7603-6750) (Ayush Chaurasia)  
> - [0000-0003-3783-7069](https://orcid.org/0000-0003-3783-7069) (Jing Qiu)

YOLOv5 Models are provided under [AGPL-3.0](https://github.com/ultralytics/ultralytics/blob/main/LICENSE) and [Enterprise](https://www.ultralytics.com/license) licenses.

## Directory Structure
```
Driver-Fatigue-Project
├── Datasets/
│   ├── Dataset_2/
│   │   ├── Original/
│   │   │   ├── Drowsy/
│   │   │   └── Non Drowsy/
│   │   ├── Processed_Images/
│   │   │   ├── train/
│   │   │   │   ├── images/
│   │   │   │   ├── labels/
│   │   │   ├── val/
│   │   │   │   ├── images/
│   │   │   │   ├── labels/
│   │   │   └── test/ 
│   │   │       ├── images/
│   │   │       ├── labels/
├── preprocessing/
│   └── data_preprocessing.ipynb
├── model/
│   ├── yolo/
│   │   ├── dataset.yml
│   │   └── yolo_object_detection.ipynb
```