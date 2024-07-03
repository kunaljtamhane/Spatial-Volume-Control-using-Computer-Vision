# Spatial-Volume-Control-using-Computer-Vision
## Overview
This project implements a spatial volume control system using computer vision techniques. Leveraging Google's Mediapipe library, a custom-built Hand Tracking module, and the Pycaw library for audio control, the system tracks the positions of the first index finger and thumb to dynamically control the volume of a device. The project showcases an innovative approach to volume control, moving away from traditional hardware buttons and sliders to a more intuitive and interactive method.

## Features
Hand Tracking: Utilizes Google's Mediapipe to detect and track hand landmarks in real-time.
Volume Control: Adjusts the device's volume based on the distance between the first index finger and thumb using the Pycaw library.
Intuitive Interface: Provides a natural and intuitive way to control volume without the need for physical contact or buttons.
Real-Time Processing: Ensures smooth and responsive volume control through efficient real-time processing of hand movements.

## Dependencies
Google Mediapipe
Pycaw
OpenCV
Numpy

**How to Control: **
Place your hand in front of the camera.
Use your first index finger and thumb to adjust the volume by bringing them closer or moving them apart.

**How It Works**
Hand Detection: The system uses Mediapipe to detect and track hand landmarks.
Distance Calculation: It calculates the distance between the first index finger and thumb.
Volume Adjustment: The distance is then mapped to the volume level of the device, using Pycaw to adjust it in real-time as the distance changes.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
