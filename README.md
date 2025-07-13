
# Push-Up Counter with Pose Detection

This project uses **MediaPipe** and **OpenCV** to detect human poses through a webcam and count push-ups in real-time by analyzing body joint angles. It’s a simple AI-powered fitness tracker that you can run locally on your machine!

![demo](assets/demo.gif)

Project Overview
Goal: Detect a user doing push-ups using a webcam and count the number of completed push-ups using pose estimation.

Technologies: Python, OpenCV, MediaPipe (or OpenPose), Numpy, optionally PyGame/Matplotlib for visualization.
---

## Features

1) Real-time pose estimation  
2) Push-up counter based on elbow/shoulder angle   Live status: “Up” / “Down”  
3) Works on standard webcam  
4) Easy to customize and extend  

---

##  Technologies Used

- [Python](https://www.python.org/)
- [MediaPipe](https://google.github.io/mediapipe/)
- [OpenCV](https://opencv.org/)
- [NumPy](https://numpy.org/)

---

## Requirements

Install the dependencies using:

```bash
pip install -r requirements.txt
