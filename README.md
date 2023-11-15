# YOLO Safety Helmet Detection

## Development Guide
- Run `make setup` to setup the development environment, and follow the instructions to setup datasets
- Run `make yolo` to run a demo of the YOLOv5 model, which will retrain the yolov8 model and make prediction for the [bus.jpg](./src/assets/img/bus.jpg) like the following:

    ![bus.jpg](./src/assets/img/bus_prediction.jpg)

- Run `make camera-detect` to run a demo of the YOLOv5 model on webcam, which will make prediction in real-time

### Useful Commands
- `make train` to train a custom YOLO model based on dataset 3
- `make clean` to clean the project setup, including the Python virtual environment and the runs folder generated by YOLO

## Object Detection Model

### Data Preprocessing
- TODO


### Model Training
- [Train Custom Data](https://docs.ultralytics.com/yolov5/tutorials/train_custom_data/)


### Model Evaluation
- TODO


### Model deployment with edge computing
- [Deploy on NVIDIA Jetson using TensorRT and DeepStream SDK](https://docs.ultralytics.com/yolov5/tutorials/running_on_jetson_nano/)



