# VirtualTryOn

VirtualTryOn is an AI-powered virtual try-on application that allows users to see how different shirts fit on their body in real time. Using computer vision and pose detection, this project dynamically adjusts the size of a shirt based on the user's body measurements and gestures for an interactive experience.

## Features

- **Real-time Virtual Try-On**: Try on shirts virtually using your webcam and see how different shirts fit you based on your shoulder width.
- **Gesture Control**: Swipe left or right to switch between different shirts.
- **Pose Detection**: Detects your body posture and adjusts shirt size accordingly.
- **Dynamic Shirt Resizing**: The shirt size automatically scales according to the user's shoulder width, providing a more personalized fit.
- **Multiple Shirt Selection**: Browse through different shirt designs by swiping with your hands.

## Requirements

- Python 3.x
- OpenCV
- cvzone
- Mediapipe
- Numpy

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/luqmaanshaik/VirtualTryOn.git
2. Install the required dependencies:

pip install opencv-python opencv-python-headless cvzone mediapipe numpy

3. Ensure your camera is connected and accessible by OpenCV.
## Usage
1. Run the application:

python virtual_tryon.py

2. Follow the on-screen instructions to use the virtual try-on feature.
3. Swipe left or right to change shirts.

## Directory Structure

VirtualTryOn/
├── Resources/
│   └── Shirts/
│       ├── shirt1.png
│       ├── shirt2.png
│       └── ...
├── virtual_tryon.py
└── README.md
. Resources/Shirts: Folder containing the shirt images you want to use in the virtual try-on.

## Contributing
. Feel free to fork this project, submit issues, and contribute improvements. If you have ideas or suggestions, don’t hesitate to open a pull request!

## Acknowledgments
. Thanks to the developers of cvzone for the PoseDetector module.
. Thanks to Mediapipe for the pose detection model.
