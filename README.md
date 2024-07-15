# Football_Analysis_using_openCV

## Introduction
This innovative project aims to revolutionize football match analysis through advanced computer vision techniques. At its core, we employ YOLO, a cutting-edge AI object detection model, to identify and monitor the movements of players, officials, and the ball throughout a match video. To enhance accuracy, we'll refine the model through additional training.

![screenshot](https://github.com/user-attachments/assets/56f5cdb2-71c6-4c16-a140-9bafc26c1556)

Our system goes beyond simple detection by implementing Kmeans clustering for jersey color analysis, enabling automatic team assignment. This feature allows us to calculate possession statistics with unprecedented precision. We've integrated optical flow algorithms to compensate for camera motion, ensuring accurate player tracking regardless of camera movement.

![output](https://github.com/user-attachments/assets/e864323e-9070-4647-8985-341d4dbd66c1)

A key innovation is our use of perspective transformation, which converts the flat video image into a 3D representation of the playing field. This breakthrough allows us to translate pixel-based measurements into real-world distances, providing precise data on player movements in meters.
The culmination of these technologies enables us to generate detailed metrics on each player's performance, including speed and total distance covered during the match. This comprehensive approach to sports analytics bridges the gap between raw video footage and actionable insights, making it an invaluable tool for coaches, analysts, and sports scientists alike.



## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Sample video
-  [Sample input video](https://drive.google.com/file/d/1Y-BULOsOt-8FRHFEt7JaxxIVEre9p5Md/view?usp=sharing)

