# ML Football Analysis

This project builds a computer vision system that analyses football footage using deep learning and machine learning. It detects players, referees, and the ball, tracks movement across frames, measures distance and speed, and provides insights into team performance.

The system combines YOLOv8 object detection, OpenCV tracking, and K-Means colour clustering to identify players, assign them to teams based on shirt colour, and applies optical flow and perspective transformation to convert pixel movement into real-world metrics. Annotated match footage is then saved with all insights overlaid.

## Raw footage
![1](demo/1.gif)

## Detect and track players, referees, and the ball using YOLOv8
![2](demo/2.gif)

## Identify team colours and assign players to teams with K-Means clustering
![3](demo/3.gif)

## Detect ball possession for each team frame by frame
![4](demo/4.gif)

## Use perspective transformation to measure player speed and distance in metres
![5](demo/5.gif)
