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
Ultralytics YOLOv5 software:
> **Ultralytics YOLOv5**  
> Author: Glenn Jocher  
> Year: 2020  
> Version: 7.0  
> License: AGPL-3.0  
> URL: [https://github.com/ultralytics/yolov5](https://github.com/ultralytics/yolov5)  
> DOI: [10.5281/zenodo.3908559](https://doi.org/10.5281/zenodo.3908559)  
> ORCID: [0000-0001-5950-6979](https://orcid.org/0000-0001-5950-6979)

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
│   │   │   ├── Images/
│   │   │   │   ├── train/
│   │   │   │   ├── val/
│   │   │   │   └── test/
│   │   │   └── Labels/  # Contains YOLO-format image annotation files
│   │   │       ├── train/
│   │   │       ├── val/
│   │   │       └── test/
├── preprocessing/
│   └── data_preprocessing.ipynb
├── model/
│   ├── yolo/
│   │   ├── dataset.yml
│   │   └── yolo_object_detection.ipynb
```