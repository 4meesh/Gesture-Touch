# Hand Gesture Touch Screen Control

This program allows you to control your computer's touch screen using hand gestures. It uses your computer's webcam to track your hand movements and translates them into touch screen interactions.

## Features

- Real-time hand tracking using MediaPipe
- Calibration system for accurate screen mapping
- Touch simulation using index finger
- Click gesture detection (thumb and index finger pinch)
- Visual feedback through webcam feed

## Requirements

- Python 3.7 or higher
- Webcam
- Touch screen display
- Required Python packages (listed in requirements.txt)

## Installation

1. Clone this repository or download the files
2. Install the required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the program:
```bash
python hand_gesture_control.py
```

2. Calibration:
   - When the program starts, it will enter calibration mode
   - Use your index finger to touch the four corners of your screen
   - Press the spacebar each time you want to record a corner point
   - The order should be: top-left, top-right, bottom-left, bottom-right
   - Press 'q' to quit calibration if needed

3. Control:
   - Use your index finger to point at different locations on the screen
   - The cursor will follow your index finger
   - To click, pinch your thumb and index finger together
   - Press 'q' to quit the program

## Notes

- Make sure your webcam has a clear view of your hand
- Good lighting conditions will improve hand tracking accuracy
- The program works best with a single hand in view
- Keep your hand movements within the calibrated area 
