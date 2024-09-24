
# Drowsiness Detection System

## Project Title: Drowsiness Detection System Using OpenCV and Raspberry Pi

## Overview
The Drowsiness Detection System is designed to monitor a user's alertness by analyzing facial expressions and eye movements through computer vision techniques. This system utilizes OpenCV, a Raspberry Pi camera, and the Media Pi framework to detect signs of drowsiness in real-time. When drowsiness is detected, the system can alert the user through visual or auditory signals.

## Features
- Real-time detection of drowsiness
- Alerts triggered upon detection of drowsiness
- Lightweight and efficient operation on Raspberry Pi
- User-friendly interface for easy operation

## Hardware Requirements
- Raspberry Pi (any model with camera support)
- Raspberry Pi Camera Module
- USB Power Supply for Raspberry Pi
- Optional: Buzzer or LED for alerts

## Software Requirements
- Raspbian OS installed on Raspberry Pi
- Python 3.x
- OpenCV library
- NumPy library
- Mediapipe library

Installation
Set up Raspberry Pi:
Install Raspbian OS on your Raspberry Pi. Update the package list:

bash
![image](https://github.com/user-attachments/assets/9de9380d-8af0-48ba-9c61-a2a50d25483e)


2. Install Required Libraries:  
  ![image](https://github.com/user-attachments/assets/d81eb5f4-79d0-431a-9e0a-b479e5773be0)

   ```

3. Clone the Repository:  
   Clone the project repository to your Raspberry Pi:  
   ```bash
   git clone <repository-url>
   cd drowsiness-detection
   ```

4. Connect the Camera:  
   Connect the Raspberry Pi Camera module and enable it using the Raspberry Pi Configuration settings.

5. Run the Application:  
   Execute the main script:  
   ```bash
   python3 drowsiness_detection.py
   ```

## Usage
Position the user in front of the camera. The system will begin analyzing the user’s facial features for signs of drowsiness. If drowsiness is detected, an alert will be triggered.

## Code Overview
- drowsiness_detection.py: This is the main script that initializes the camera, processes the video stream, and implements the drowsiness detection logic.
- models/: This directory contains any pre-trained models, if applicable.
- requirements.txt: This file lists all necessary Python libraries for easy installation.

## Contributing
Contributions are welcome. Please open an issue or submit a pull request for any suggestions or improvements.

## License
This project is licensed under the MIT License. For more information, please refer to the LICENSE file.

## Acknowledgments
- OpenCV team for the powerful library.
- Mediapipe for providing efficient models for face and eye detection.
- Community contributors for valuable resources and support.
