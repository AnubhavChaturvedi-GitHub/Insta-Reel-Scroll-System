# Hand Gesture Controlled Scrolling

This project uses MediaPipe and OpenCV to detect hand gestures and perform corresponding actions, specifically controlling the scroll function using the index and middle finger tips.

## Features

- Detects hand gestures using MediaPipe.
- Controls scrolling actions based on the position of the index and middle finger tips.
- Displays visual feedback on the screen for the detected gestures.

## Requirements

- Python 3.11.4
- OpenCV
- MediaPipe
- PyAutoGUI
- NumPy

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/AnubhavChaturvedi-GitHub/Insta-Reel-Scroll-System.git
    cd HandGestureControlledScrolling
    ```

2. Install the required packages:
    ```bash
    pip install opencv-python mediapipe pyautogui numpy
    ```

## Usage

1. Run the main script:
    ```bash
    python hand_gesture_scrolling.py
    ```

2. A window will open displaying the camera feed. Use your hand to perform gestures:
    - Move the index and middle finger close together to start scrolling.
    - Raise the index finger higher than the middle finger to scroll up.
    - Lower the index finger below the middle finger to scroll down.

3. Press 'q' to quit the application.

## Code Overview

### Importing Libraries
```python
import cv2
import mediapipe as mp
import pyautogui
import numpy as np
```

### Function Definitions

- `get_distance(a, b)`: Calculates Euclidean distance between two points.
- `find_finger_tips(processed)`: Finds the tips of the index and middle fingers.
- `is_scroll(landmark_list)`: Detects if a scroll gesture is made.
- `detect_gesture(frame, landmark_list, processed)`: Detects gestures and performs corresponding actions.

### Main Function

- `MCV()`: Initializes the camera, processes the frames to detect gestures, and controls scrolling based on the detected gestures.

## Links

- **Instagram:** [Anubhav Chaturvedi](https://www.instagram.com/_anubhav__chaturvedi_/)
- **Facebook:** [Indian Youtuber and Software Developer](https://www.facebook.com/IndianYoutuberAndSoftwareDevloper)
- **Linktree:** [Allorizen](https://linktr.ee/allorizen)
- **Portfolio:** [Anubhav Chaturvedi](https://anubhavchaturvedipro-portfolio.netlify.app)
- **LinkedIn:** [Anubhav Chaturvedi](https://linkedin.com/in/anubhav-chaturvedi-)
- **Twitter:** [Anubhav Chaturvedi](https://twitter.com/AnubhavChatu)
- **GitHub:** [Anubhav Chaturvedi](https://github.com/AnubhavChaturvedi-GitHub)
- **YouTube (NetHyToons):** [NetHyToons](https://www.youtube.com/@nethytoons)
- **YouTube (Anubhav Chaturvedi):** [Anubhav Chaturvedi](https://www.youtube.com/@Anubhav_Chaturvedi)
- **Geeks for Geeks:** [Chaturvedianubhav520](https://auth.geeksforgeeks.org/user/chaturvedianubhav520)
- **LeetCode:** [Ac520](https://leetcode.com/Ac520)
- **Telegram Channel:** [Jarvis by Anubhav Chaturvedi](https://t.me/JarvisByAnubhavChaturvedi)
- **Instagram:** [Anubhav Chaturvedi](https://www.instagram.com/_anubhav__chaturvedi_/)

## License

This project is licensed under the MIT License.



For any questions or contributions, please feel free to reach out through the provided social media links.
