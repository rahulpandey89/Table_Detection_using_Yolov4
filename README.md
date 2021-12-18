# Table_Detection_using_Yolov4
This repository detects table used in table tennis game using yolov4 pretrained model
I have 1000.png file which contains image along with annotations.xlsx contains below information:
top_left=(x_min,y_min)
top_right=(x_max,y_min)
bottom_left=(x_min,y_max)
bottom_right=(x_max,y_max)
First I calculated x,y,w,h using below formual:
x_min=x
y_min=y
w=x_max-x_min
h=y_max-ymin

Step 2))): I converted bounding box coordinates to yolo form added class using convert.py python code and did save it in local machine. Now i have 2 folder one with all images and Labels for each images one text file containing bounding boxes coordinates
