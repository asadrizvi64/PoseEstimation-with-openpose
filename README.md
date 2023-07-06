# OpenPose Pose Detection

This repository contains code that utilizes OpenPose, a pre-trained model, to detect human pose in images and videos. OpenPose is an open-source pose estimation library that can estimate the 2D position of body joints, such as the nose, shoulders, elbows, wrists, hips, knees, and ankles.

## Requirements

- OpenCV (cv2)
- Matplotlib
- Google Colab patches

## Installation

To run the code, you need to have the required dependencies installed. You can install them using the following command:

```shell
pip install opencv-python matplotlib
```
## Usage
### Pose Detection in Images

1. Replace the 'pose.jpg' file with your own image file that you want to perform pose detection on.
2. Run the code to detect the pose in the image.

The code will display the input image with the detected body joints and pose connections.

### Pose Detection in Images

1. Replace the 'self.mp4' file with your own video file that you want to perform pose detection on. Alternatively, if no video file is provided, the code will use the webcam to capture live video.
2. Run the code to detect the pose in the video.

The code will display each frame of the video with the detected body joints and pose connections in real-time.

## Customization
You can customize the code to suit your specific needs. For example, you can adjust the confidence threshold for body joint detection (thr) to filter out low-confidence detections or modify the pose connections by editing the 'POSE_PAIRS' list.

## Acknowledgments
The code in this repository is based on the OpenPose library and its pre-trained model. The original code and model can be found at:
- https://github.com/CMU-Perceptual-Computing-Lab/openpose

## References
- OpenPose: Real-time multi-person keypoint detection library for body, face, hands, and foot estimation

  
~Please note that this README.md assumes the user is familiar with using Python, libraries like OpenCV and Matplotlib, and running code in a Jupyter Notebook or similar environment.
