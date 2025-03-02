# Interactive Zoom Effect with Hand Gestures

This project demonstrates an interactive zoom effect controlled by hand gestures using OpenCV and `cvzone.HandTrackingModule`. Users can dynamically resize an image in real-time by moving their hands in front of a webcam. The zoom gesture is detected when both hands are visible, and specific finger combinations are used.

## Features
- **Real-Time Hand Detection**: Uses OpenCV to detect and track hand movements via a webcam.
- **Dynamic Scaling**: Zooms in and out of an image based on the distance between index fingers.
- **Responsive Placement**: The image dynamically updates its size and position to follow hand gestures.
- **Cross-Platform Compatibility**: Works on Windows, macOS, and Linux with a compatible webcam.

## How It Works
1. The program captures live video from the webcam using OpenCV.
2. The `cvzone.HandTrackingModule` detects hands and tracks finger positions.
3. When two hands are detected with the index and middle fingers extended on both hands, the distance between their index fingertips is measured.
4. The change in distance is used to scale the displayed image dynamically.
5. The scaled image is centered between the hands for a natural zooming experience.

## Requirements
Ensure you have the following installed before running the project:
- Python 3.x
- OpenCV (`pip install opencv-python`)
- cvzone (`pip install cvzone`)

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/interactive-zoom.git
   cd interactive-zoom
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python main.py
   ```

## Usage
- Ensure your webcam is connected and positioned correctly.
- Start the program and place both hands in front of the camera.
- Extend the index and middle fingers on both hands.
- Move your hands closer to zoom in and further apart to zoom out.
- The image will dynamically adjust based on your hand movements.

## Demo
[Insert a GIF or image demonstrating the zoom effect in action]

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing
Feel free to submit pull requests or open issues to improve the project!

---
Happy coding! 🚀

