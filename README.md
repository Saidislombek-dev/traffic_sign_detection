# Traffic sign detection and classification using [YOLOv8](https://docs.ultralytics.com)

## Datasets
 - for detection > [Traffic Signs Dataset in YOLO format](https://www.kaggle.com/datasets/valentynsichkar/traffic-signs-dataset-in-yolo-format)
 - for classification > [GTSRB - German Traffic Sign Recognition Benchmark](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)

## Train
 - training process is not shown
 - some areas of the datasets are modified and not fully used
 - you can see only detection train [results](https://github.com/Saidislombek-dev/traffic_sign_detection/tree/main/detection_train)
 - traffic signs are detect in the following four groups

### These are:
 1. prohibitory
 
 ![img](images/prohibitory.png)
 
 2. danger
 
 ![img](images/danger1.png)
 
 ![img](images/danger2.png)
 
 3. mandatory
 
 ![img](images/mandatory1.png)
 
 ![img](images/mandatory1.png)
 
 4. other
 
 ![img](images/other.png)


### Note: Detection model can detect many signs but classification model can be divided into the classes shown in the picture above!

## Test
 - [Main file](Main.ipynb) shows the usage of the model
 - you can check your test file yourself
 - code is also written for the file in video format

## Example

![img](images/result.png)
### **That's why it find some character names wrong in the example picture
