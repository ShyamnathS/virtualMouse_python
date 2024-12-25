# Virtual Mouse using Hand Gestures

This project implements a virtual mouse that allows you to control your computer's cursor and perform clicks using hand gestures. The system uses the webcam to track the movement of your hand, and it utilizes the **MediaPipe** library for hand tracking and **PyAutoGUI** for controlling the mouse cursor and simulating clicks.

## Features

- **Hand Gesture Tracking**: Detects and tracks the position of the index finger and thumb.
- **Mouse Movement**: Moves the mouse cursor based on the movement of your index finger.
- **Click Simulation**: Simulates mouse clicks when the index finger and thumb come close to each other.
- **Real-Time Interaction**: Provides real-time tracking and control of the cursor on your screen.

## Requirements

- Python 3.x
- **OpenCV**: For handling video feed from the webcam.
- **MediaPipe**: For hand tracking.
- **PyAutoGUI**: For controlling the mouse and performing clicks.

You can install the required libraries using:

```bash
pip install opencv-python mediapipe pyautogui
