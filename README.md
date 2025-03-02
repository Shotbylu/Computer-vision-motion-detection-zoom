# Interactive Zoom Effect with Hand Gestures

This project demonstrates an interactive zoom effect controlled by hand gestures using OpenCV and cvzone.HandTrackingModule. Users can dynamically resize an image in real-time by moving their hands in front of a webcam. The zoom gesture is detected when both hands are visible, and specific finger combinations are used.

Features

Real-Time Hand Detection: Uses OpenCV to detect and track hand movements via a webcam.

Dynamic Scaling: Zooms in and out of an image based on the distance between index fingers.

Responsive Placement: The image dynamically updates its size and position to follow hand gestures.

Cross-Platform Compatibility: Works on Windows, macOS, and Linux with a compatible webcam.

How It Works

The program captures live video from the webcam using OpenCV.

The cvzone.HandTrackingModule detects hands and tracks finger positions.

When two hands are detected with the index and middle fingers extended on both hands, the distance between their index fingertips is measured.

The change in distance is used to scale the displayed image dynamically.

The scaled image is centered between the hands for a natural zooming experience.

Requirements

Ensure you have the following installed before running the project:

Python 3.x

OpenCV (pip install opencv-python)

cvzone (pip install cvzone)

Installation

Clone this repository:

git clone https://github.com/yourusername/interactive-zoom.git
cd interactive-zoom

Install dependencies:

pip install -r requirements.txt

Run the script:

python main.py

Usage

Ensure your webcam is connected and positioned correctly.

Start the program and place both hands in front of the camera.

Extend the index and middle fingers on both hands.

Move your hands closer to zoom in and further apart to zoom out.

The image will dynamically adjust based on your hand movements.
