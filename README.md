# Hand Gesture Recognition for Mouse Control and Application Launch

This project allows you to control your computer using hand gestures through your webcam. The gestures include:

- **Left Click**: Triggered when the thumb and index finger tips are close.
- **Right Click**: Triggered when the thumb and middle finger tips are close.
- **Mouse Movement**: Controlled by the position of the index finger tip.
- **Application Launch**: Triggered by making a fist gesture (e.g., opens Notepad).

It utilizes Python along with **OpenCV**, **MediaPipe**, and **PyAutoGUI** for detecting hand gestures and simulating mouse actions.

---

## Features

- **Left Click Gesture**: Triggered when the thumb and index finger are near each other.
- **Right Click Gesture**: Triggered when the thumb and middle finger are near each other.
- **Mouse Movement**: The index finger's position is used to control the mouse cursor.
- **Application Launch**: Launch an application (e.g., Notepad) when a fist gesture is detected.

---

## Requirements

To run this project, you need to install the following Python dependencies:

- OpenCV
- MediaPipe
- PyAutoGUI
- Screeninfo
- PyWin32

You can install them using `pip`:

```bash
pip install -r requirements.txt
