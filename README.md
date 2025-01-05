# Virtual Mouse Using Hand Gestures

This project
This project implements a virtual mouse using hand gestures with OpenCV, NumPy, and a hand tracking library. The project captures hand movements via a webcam and maps them to mouse actions on the screen using the `autopy` library.

## Features
- Control the mouse cursor using hand movements.
- Left click using a pinching gesture (bringing the index and middle fingers close together).
- Smooth cursor movement with adjustable smoothing factor.

## Technologies Used
- **Python**: Core language used for development.
- **OpenCV**: Used for capturing video input from the webcam and processing images.
- **NumPy**: For numerical operations.
- **Hand Tracking Module**: Custom or third-party library for detecting and tracking hand landmarks.
- **Autopy**: For controlling the mouse pointer programmatically.

## Setup and Installation

### Prerequisites
- Python 3.x
- Libraries: `opencv-python`, `numpy`, `autopy`
- Hand tracking library (custom or from a source like MediaPipe).

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/virtual-mouse.git
   cd virtual-mouse
2. install the requirement.text
    ```bash
     pip install -r requirements.txt
3. Optionally, install MediaPipe for hand tracking:
   ```bash
     pip install mediapipe
4.Run the program:
```bash
     python virtual_mouse.py

