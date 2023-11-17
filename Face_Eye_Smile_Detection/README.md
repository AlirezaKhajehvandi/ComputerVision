# Face Detection with OpenCV

This repository contains a simple Python script for face detection using OpenCV. The script utilizes Haar cascades for face, eye, and smile detection.

## Prerequisites

Before running the script, make sure you have the required libraries installed:

```bash
pip install opencv-python
```


## Usage
### 1. Clone the repository:
```bash
git clone https://github.com/AlirezaKhajehvandi/ComputerVision.git
cd Face_Eye_Smile_Detection
```

### 2. Download the Haar cascades XML files or use them from this repo:
![GitHub](https://github.com/opencv/opencv/tree/master/data/haarcascades)

### 3. Run the script:
```bash
python Smile_detection.py
```

The script will open your webcam and perform face detection in real-time.

### 4. Press 'q' to exit the video window.


## Script Explanation

* The script uses Haar cascades for face, eye, and smile detection.
* The `detect` function is defined to perform the actual detections on each frame.
* Face rectangles are drawn in green, eye rectangles in yellow, and smile rectangles in red.
* If a smile is detected, the script adds text to the frame indicating "You're smiling."


Feel free to modify the script and customize it according to your needs.


License
This project is licensed under the `MIT License`.