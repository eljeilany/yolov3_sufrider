# yolov3_sufrider
This repo provides an easy way to train and benchmark

Yolo3 the ultralytics Pytorch implementation: https://github.com/ultralytics/yolov3
on the surfider object detection dataset

The implementation was changed to improve it's performance on surfider
Mainly the Exponential Moving weight Averaging was removed and some other training and hyper parametres finetuning.

Changed files are:
train.py
test.py
utils/torch_utils

train/validation split is .86

Final all classes acheived mPA is 79.43%

# Runing:
## Data preparation: 
**Execute all cells in the convert_dataset.ipynb notebook**
## training and validation: 
**Execute all cells in the train_and_validate.ipynb notebook**

