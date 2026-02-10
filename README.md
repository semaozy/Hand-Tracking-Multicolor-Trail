# 🖐️ Hand Tracking: Multicolor Finger Trail

This project utilizes the **MediaPipe** library for real-time hand tracking and creates a dynamic visual trail by drawing lines in a different color for the movement of each individual fingertip.

## ✨ Features

* **Real-Time Tracking:** Processes the live video stream from a webcam instantly.
* **Multicolor Trail:** Draws separate colored lines for the tips of the index, middle, ring, and pinky fingers.
* **Trail Length Control:** The persistence (number of points) of the lines on the screen can be adjusted.
* **FPS Display:** Shows the processing speed (Frames Per Second - FPS) on the screen.

## ⚙️ Requirements

To run this project locally, the following Python libraries are required:

* Python 3.x
* OpenCV (`cv2`)
* MediaPipe (`mediapipe`)
* NumPy (`numpy`)

### Installation

You can install all necessary libraries by running the following command in your terminal (or Notebook):

pip install opencv-python mediapipe numpy

### 🚀 Usage
Follow these steps to run and use the project:

Execute Code Blocks: Run the project code (typically a Jupyter Notebook or a standalone Python file) sequentially.

Camera Activation: A separate window will open, displaying the live video feed from your webcam.

Hand Movement: Bring your hand into the camera's view. Once MediaPipe detects the hand, colored trails will appear behind your fingertips.

Index Finger: Blue (default)

Middle Finger: Green (default)

Ring Finger: Red (default)

Pinky Finger: Magenta (default)

Exit: Press the q key while the display window is active to safely terminate the program.

### by sema
