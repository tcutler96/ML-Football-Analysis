# ML Football Analysis

This project builds a computer vision system that analyses football footage using AI and machine learning. It detects players, referees, and the ball, tracks movement across frames, measures distance and speed, and provides insights into team performance.

The system combines YOLOv8 object detection, OpenCV tracking, and KMeans colour clustering to identify players, assign them to teams based on shirt colour, and applies optical flow and perspective transformation to convert pixel movement into real-world metrics. The project demonstrates key skills in deep learning, object detection, tracking, and data-driven sports analysis.

## Main Features:
- Detect and track players, referees, and the ball using YOLOv8
- Estimate camera movement and adjust object positions for accurate tracking
- Use perspective transformation to measure player speed and distance in metres
- Identify team colours and assign players to teams with KMeans clustering
- Detect ball possession for each team frame by frame
- Save annotated match footage with all insights overlaid

![Demo](demo/demo.gif) 
