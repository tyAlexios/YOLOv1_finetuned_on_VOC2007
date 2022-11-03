run train.py to train the model
run predict to predict new data

This is a YOLOv1 based on the dataset VOC2007.
If we want to train it to recognize different kinds of waste to do waste sorting, we need the data of waste and change the class_set and even the size of tensor. (This tensor is 7*7*30 which can recognize 20 classes)