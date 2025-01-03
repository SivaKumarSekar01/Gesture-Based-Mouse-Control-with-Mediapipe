Gesture-Controlled Mouse System
A Python-based system that enables hands-free computer control using webcam-detected hand gestures. Control your mouse cursor, perform clicks, and capture screenshots using natural hand movements.
Features

👆 Cursor control using index finger
🖱️ Left, right, and double click gestures
📸 Screenshot capture functionality
🎯 Real-time hand tracking
⚡ Low-latency response

Prerequisites

Python 3.8+
Webcam
Internet connection (for initial MediaPipe model download)

Installation

Clone the repository:

bashCopygit clone https://github.com/yourusername/gesture-mouse
cd gesture-mouse

Install required packages:

bashCopypip install -r requirements.txt
Usage
Run the main script:
bashCopypython main.py
Supported Gestures
GestureActionDescriptionPoint with index fingerMove cursorMove your index finger to control cursor positionIndex bent, middle straightLeft clickBend index finger while keeping middle finger straightMiddle bent, index straightRight clickBend middle finger while keeping index finger straightBoth fingers bentDouble clickBend both index and middle fingersThumb-index pinchScreenshotPinch thumb and index finger together
Dependencies
pythonCopyopencv-python==4.8.0
mediapipe==0.10.0
pyautogui==0.9.54
numpy==1.24.3
pynput==1.7.6
Code Structure

main.py: Core application and webcam handling
Gesture detection modules:

Hand landmark tracking
Gesture recognition
Mouse control interface



Performance Tips

Ensure good lighting conditions
Keep your hand within camera frame
Maintain 30-60cm distance from camera
Use contrasting background

Contributing

Fork the repository
Create your feature branch (git checkout -b feature/amazing-feature)
Commit changes (git commit -m 'Add amazing feature')
Push to branch (git push origin feature/amazing-feature)
Open Pull Request

License
Distributed under the MIT License. See LICENSE for more information.
Acknowledgments

MediaPipe for hand tracking
OpenCV for image processing
PyAutoGUI for mouse control

Contact
Your Name - @yourtwitter
Project Link: https://github.com/yourusername/gesture-mouse
