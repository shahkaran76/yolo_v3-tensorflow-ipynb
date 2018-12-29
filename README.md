# yolo_v3-tensorflow-ipynb
This repository explains you how to convert the yolo v3 darknet model into tensorflow model and run it in jupyter notebook with python3.


## 1 What is YOLO?

‘You Only Look Once’ is an Object Detection Algorithm. So what’s great about object detection? In
comparison to recognition algorithms, a detection algorithm does not only predict class labels but
detects locations of objects as well. So, It not only classifies the image into a category, but it can also
detect multiple Objects within an Image. And this Algorithm doesn’t depend on multiple Neural
networks. It applies a single Neural network to the Full Image. This network divides the image
into regions and predicts bounding boxes and probabilities for each region. These bounding boxes
are weighted by the predicted probabilities.

![alt text](https://github.com/shahkaran76/yolo_v3-tensorflow-ipynb/blob/master/output_54_10.png)

![alt text](https://github.com/shahkaran76/yolo_v3-tensorflow-ipynb/blob/master/output_54_4.png)

## 2  Why this Notebook?

The original YOLO algorithm is deployed in Darknet. Darknet is an open source neural network
framework written in C and CUDA. We will deploy this Algorithm in Tensorflow with Python.

## 3  Dependencies

To build the YOLO we will require : 
1. Tensorflow (GPU version preferred for Deep Learning)
2. NumPy (for Numeric Computation)
3. Pillow/PIL (for Image Processing)
4. IPython (for displaying images in Jupyter Notebook) 
5. Glob (for finding pathname of all the files in a folder)

## 4  Acknowledgements

YOLO - https://pjreddie.com/darknet/yolo/
