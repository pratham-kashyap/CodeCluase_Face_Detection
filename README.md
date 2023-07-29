# Face Detection using OpenCV

This repository contains a Python script for real-time face detection using OpenCV's Haar Cascade Classifier. It captures frames from the webcam, detects faces in each frame, and highlights the detected faces with rectangles.

## Requirements

To run this script, you need to have the following installed on your system:

- Python 3.x
- OpenCV library (cv2)

You can install OpenCV using pip:
`pip install opencv-python`

## How to Use

1. Clone this repository to your local machine or simply copy the code from the provided `main.py` file.

2. Make sure your webcam is connected and functioning correctly.

3. Run the script using the following command:
   `python main.py`

4. The script will open a window showing the webcam feed with detected faces outlined by white rectangles.

5. To exit the program, press the 'q' key.

## About the Code

The main script `main.py` contains the following functionality:

- Imports the required libraries, including OpenCV (`cv2`).

- Loads the pre-trained Haar Cascade Classifier for face detection.

- Captures frames from the default webcam using OpenCV's `VideoCapture` class.

- Converts each frame to grayscale for face detection.

- Detects faces in the grayscale frame using the Haar Cascade Classifier.

- Draws rectangles around the detected faces using the `cv2.rectangle` function.

- Displays the webcam feed with detected faces in real-time.

- The loop continues until the 'q' key is pressed, and then the webcam is released, and all windows are closed.

Feel free to modify the code as per your requirements and explore further possibilities with OpenCV!
