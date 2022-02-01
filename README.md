# DL-ML-Assignment
The goal of this task is to train a model that can localize and classify each instance of person and car as accurately as possible.

🔴 What is **Object Detection** and the popular object detection algorithm ?

*The task of knowing what’s present in an image is classification.

*The task of knowing where a certain thing is present in an image is localization

*Finally, the task of knowing what is present in the screen and also where it is present is known as object detection. You can call it the combination of both image classification and localization.

![object-detection-popular-algorithms](https://user-images.githubusercontent.com/34507725/151908663-c5d5fad7-dab3-4d59-8c36-a0f3ba9059e1.png)

🔴 About the model **Yolo v5**

This approach uses a single neural network to process the entire picture, then separates it into parts and predicts bounding boxes and probabilities for each component. The method “just looks once” at the image in the sense that it makes predictions after only one forward propagation run through the neural network.

🔴 Primary analysis, Approach, Metrics used.

There are a lot of available types of algorithms for this task. YOLO is one of the most famous models in this category of object detection and is fast, reliable, and accurate.

To use Yolo v5 we have converted json based annotation to text based annotations as yolo do not support json.

There are various metrics used to measure the accuracy and performance of an object detection model – precision, recall, and mAP at various levels just to name a few. We can even combine these metrics to form a new average metric to judge the performance. But none of these metrics capture the whole picture because, as sometimes judging the performance is a subjective task.

🔴 Solution Overview

We created a yolo v5 custom object detection model that can successfully recognize **PERSON** and **CARS** in an efficient way.

**best.pt** is the custom training model.

🔴 Files for multiple purpose mentioned below

🟢 For file conversion, please refer to : code to coco to yolo.ipynb,

🟢 For data preparation, please refer to : data prep.ipynb,

🟢 For Model Building and testing please refer to: yolo_new_final.ipynb

