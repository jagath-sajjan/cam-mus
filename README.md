**Hand Tracking and Mouse Control**
=====================================

**Control your mouse with hand gestures!**

### Overview

This repository contains a Python script that uses OpenCV and MediaPipe to track hand landmarks and control the mouse cursor. The script uses the webcam to detect hand gestures and moves the mouse cursor accordingly.

### Support the developer

<script type="text/javascript" src="https://cdnjs.buymeacoffee.com/1.0.0/button.prod.min.js" data-name="bmc-button" data-slug="jagathsajjan" data-color="#FFDD00" data-emoji="☕"  data-font="Poppins" data-text="Buy me a coffee" data-outline-color="#000000" data-font-color="#000000" data-coffee-color="#ffffff" ></script>

### Requirements

| Package | Version |
| Python | 3.6+ |
| OpenCV | 4.5+ |
| MediaPipe | 0.8+ |
| PyAutoGUI | 0.9+ |

### Installation

Step 1: ```git clone https://github.com/jagathsajjan/cam-mus.git```
#
Step 2: ```cd cam-mus```
#
Step 3: ```pip install -r requirements.txt```

### Usage

1. Run the script: python main.py
2. The script will open a window displaying the webcam feed.
3. Move your hand in front of the webcam to control the mouse cursor.
4. The script will track the tip of your index finger and thumb.
5. When your thumb and index finger are close together, the script will simulate a mouse click.

### Features

-> Hand tracking using MediaPipe
-> Mouse control using PyAutoGUI
-> Adjustable sensitivity

### Contributing
Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.

### License

MIT License

### Author

[jagathsajjan]