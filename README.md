# Change Shirt using Computer Vision

## Overview
The "Change Shirt" project is a Python application that utilizes computer vision to dynamically change a person's shirt in real-time using a webcam. The application tracks key points on the user's upper body and overlays different shirt designs based on user gestures.

## Features
- **Real-time Shirt Change:** Change your virtual shirt in real-time using hand gestures.
- **Dynamic Shirt Sizing:** The application dynamically adjusts the size of the shirt based on the user's body proportions.
- **Interactive User Interface:** Use hand gestures to navigate through a collection of available shirts.

## Requirements
- Python 3.x
- OpenCV
- cvzone (a Python library for computer vision)

## Getting Started
1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/change-shirt-cv.git
   cd change-shirt-cv

**
Install the required dependencies:
**
pip install opencv-python cvzone
Run the application:
python change_shirt.py

**
Usage
**
Change Shirt: Move your hands to the right or left to cycle through available shirt designs.
Interaction Buttons: Virtual buttons on the screen for changing shirts.

**Project Structure
**
change_shirt.py: Main application script.
Resources/Shirts/: Folder containing different shirt designs.
Resources/button.png: Image files for interactive buttons.

**Acknowledgments
**
This project uses the cvzone library for enhanced computer vision functionalities.
