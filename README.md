# S23-AML-Assignment-1
## Detection of street lights and security cameras
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FleshRazer/S23-AML-Assignment-1/blob/main/Assignment-1.ipynb)

## 1. Dataset collection
The dataset was collected over two days with different lighting and weather.

![image](readme/Screenshot%20from%202023-03-06%2020-32-53.png)

## 2. Dataset annotation
The dataset was annotated using Roboflow, and can be accessed via the [link](https://universe.roboflow.com/s23appliedmachinelearning/iu-s23-aml-assignment-1/dataset/1).

![image](readme/Screenshot%20from%202023-03-06%2021-26-14.png)

## 3. Faster RCNN training
The faster RCNN model was trained using [detectron2](https://github.com/facebookresearch/detectron2).

![image](readme/Screenshot%20from%202023-03-11%2000-35-52.png)

## 4. YOLOv8 training
The YOLO v8 nano was trained using [ultralytics](https://github.com/ultralytics/ultralytics).

![image](readme/Screenshot%20from%202023-03-11%2000-34-52.png)

## 5. Faster RCNN and YOLOv8 comparison
| Model | MAP | Inference time | Size |
| --- | --- | --- | --- |
| Faster RCNN | 0.229 | 336.2 ms | ~720 mbs |
| YOLOv8 nano | 0.353 | 3.8 ms | ~5.9 mbs |
