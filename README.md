Pose Estimation using Mediapipe

This repository contains a Python script that uses Mediapipe and OpenCV libraries to perform pose estimation on a video file. The script reads frames from the video file and applies pose estimation on each frame to detect the body posture of the person in the video.

Requirements
Python 3.x
OpenCV (cv2)
Mediapipe
You can install OpenCV and Mediapipe using pip:
pip install opencv-python mediapipe


Usage
Clone this repository:
git clone https://github.com/username/repo.git

Navigate to the directory:
cd repo

Run the script:
python pose_estimation.py

By default, the script uses a video file named 1.mp4 in the PoseVideos directory. You can replace this file with your own video file or modify the script to use a webcam feed instead.

Output
The script displays the input video with the detected poses overlaid on top of the video frames. Each pose is represented by a set of landmarks (keypoints) that define the positions of various body parts.

Credits
Mediapipe
OpenCV
Pose Estimation using Mediapipe
