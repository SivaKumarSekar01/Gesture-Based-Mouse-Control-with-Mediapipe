# Gesture-Controlled Mouse System

A Python-based system that enables hands-free computer control using webcam-detected hand gestures. Control your mouse cursor, perform clicks, and capture screenshots using natural hand movements.

## Features

- 👆 **Cursor control** using the index finger
- 🖱️ Perform **left, right, and double clicks** with gestures
- 📸 **Screenshot capture** functionality
- 🎯 **Real-time hand tracking** for smooth interaction
- ⚡ **Low-latency response** for seamless control

## Prerequisites

- **Python** 3.8+
- A **Webcam**
- **Internet connection** (for initial MediaPipe model download)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/gesture-mouse
cd gesture-mouse
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage

Run the main script:
```bash
python main.py
```

## Supported Gestures

| Gesture | Action | Description |
|---------|--------|-------------|
| Point with index finger | Move cursor | Move your index finger to control cursor position |
| Index bent, middle straight | Left click | Bend index finger while keeping middle finger straight |
| Middle bent, index straight | Right click | Bend middle finger while keeping index finger straight |
| Both fingers bent | Double click | Bend both index and middle fingers |
| Thumb-index pinch | Screenshot | Pinch thumb and index finger together to capture a screenshot |

## Dependencies

```python
opencv-python==4.8.0
mediapipe==0.10.0
pyautogui==0.9.54
numpy==1.24.3
pynput==1.7.6
```

## Code Structure

- `main.py`: Core application and webcam handling
- **Gesture detection modules**:
  - Hand landmark tracking
  - Gesture recognition
  - Mouse control interface

## Performance Tips

- Ensure **good lighting conditions** for better hand detection
- Keep your hand within the **camera frame** at all times
- Maintain a **30-60cm distance** from the camera
- Use a **contrasting background** for optimal performance

## Contributing

1. Fork the repository
2. Create your feature branch:
```bash
git checkout -b feature/amazing-feature
```
3. Commit your changes:
```bash
git commit -m 'Add amazing feature'
```
4. Push to the branch:
```bash
git push origin feature/amazing-feature
```
5. Open a Pull Request



## Acknowledgments

- **MediaPipe** for hand tracking
- **OpenCV** for image processing
- **PyAutoGUI** for mouse control

