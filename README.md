# Football Analysis Project

## Introduction
The goal of this project is to detect and track players, referees, and footballs in a video using YOLO, one of the best AI object detection models available. I will also train the model to improve its performance. Additionally, I will assign players to teams based on the colors of their t-shirts using Kmeans for pixel segmentation and clustering. With this information, I can measure a team's ball acquisition percentage in a match. I will also use optical flow to measure camera movement between frames, enabling me to accurately measure a player's movement. Furthermore, I will implement perspective transformation to represent the scene's depth and perspective, allowing me to measure a player's movement in meters rather than pixels. Finally, I will calculate a player's speed and the distance covered. After the YOLO analysis, annoated video and logs of detected events (Passes, Goals, Pressure, Posession Chage) are embedded into a FAISS index for NLP-based similarity search of the video.

![Screenshot](output_videos/screenshot.png)

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player
- FAISS index and embeddigs for captions

## Trained Models
- [Trained Yolo v5](https://drive.google.com/file/d/1DC2kCygbBWUKheQ_9cFziCsYVSRw6axK/view?usp=sharing)

## Sample video
-  [Sample input video](https://drive.google.com/file/d/1t6agoqggZKx6thamUuPAIdN_1zR9v9S_/view?usp=sharing)

## Requirements
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas
