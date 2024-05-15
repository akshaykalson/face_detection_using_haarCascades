Face Detection using Haar Cascades
This repository contains a Python script for real-time face detection using Haar cascades with OpenCV, this technology is also used by many camera manufacturers to detect faces in scene. The script captures video from the webcam and applies face detection on each frame, drawing rectangles around detected faces.

Prerequisites
Python 3.x
OpenCV (cv2) library
Installation
1.Clone the repository:
 git clone https://github.com/yourusername/face_detection_using_haarCascades.git
2.Install the required Python dependencies:
 pip install opencv-python
3.Download the Haar cascade XML file for frontal face detection from OpenCV's GitHub repository here and place it in the resources directory of this project.

Usage
Run the Python script:

python face_detection.py
The script will open a window showing the webcam feed with rectangles drawn around detected faces.

Press ESC key to exit the program.

Customization
You can adjust the parameters of the detectMultiScale function for better face detection accuracy. Parameters like scaleFactor and minNeighbors can be modified within the script.

To detect faces in images rather than live video, uncomment the line to load an image (img = cv2.imread('path_to_your_image.jpg')) and comment out the line to capture video from the webcam (cap = cv2.VideoCapture(0)).
