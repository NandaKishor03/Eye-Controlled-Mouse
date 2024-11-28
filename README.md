# Eye-Controlled-Mouse
This project demonstrates an eye-controlled mouse cursor using OpenCV and Mediapipe. The application leverages the power of computer vision to track eye movements and control the mouse pointer on the screen. This can be particularly useful for people with disabilities or for creating innovative human-computer interaction systems.

Features
Real-time head tracking using a webcam.
Moves the mouse cursor based on the position of the head, using the right eye as a fixed point.
Simulates mouse clicks by detecting the closure of the left eye.
Utilizes Mediapipe's Face Mesh for precise facial landmark detection.

Installation
To run this project, you need to have Python and the necessary libraries installed.

Prerequisites
Python 3.x
OpenCV
Mediapipe
PyAutoGUI

Script Explanation
The script captures the webcam feed using OpenCV.
Mediapipe's Face Mesh solution is used to detect facial landmarks.
The position of the head is determined by tracking the right eye's landmarks and mapped to the screen coordinates.
PyAutoGUI is used to move the mouse cursor and simulate clicks when the left eye is closed.

Acknowledgements
Mediapipe for providing the Face Mesh solution.
OpenCV for the powerful computer vision library.
PyAutoGUI for the automation library to control the mouse and keyboard.