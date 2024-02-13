
# Mediapipe Pose Detection and Curl Counter

This project utilizes Mediapipe, OpenCV, and Python to perform real-time pose detection and curl counting using webcam feeds. 
It is particularly useful for tracking and counting repetitions during exercises like bicep curls.

## Features

- Real-time pose detection using Mediapipe's Pose module
- Calculation of angles between specific body landmarks
- Curl counting based on defined angles for upward and downward movements
- Visualization of curl count and current stage (up or down)

## Requirements

- Python 
- OpenCV 
- Mediapipe 
- NumPy 

## Installation

1. Clone the repository to your local machine:

    ```
    git clone https://github.com/AshadullahDanish/exercise_detection_reps_couner.git
    ```

2. Install the required dependencies:

    ```
    pip install -r requirements.txt
    ```

## Usage

1. Run the script `exercise_detection_reps_couner.py`:

    ```
    exercise_detection_reps_couner.py
    ```

2. Ensure your webcam is correctly set up and captures your body movements.

3. Perform bicep curls within the webcam's view.

4. The application will display real-time curl counts and stages (up or down).

## Customization

- You can adjust the angle thresholds for curl detection by modifying the `angle` variable in the script.
- Feel free to explore and customize the code to fit your specific use case or integrate it into other applications.

## Acknowledgments

- This project was inspired by the Mediapipe Pose Detection and aims to provide a practical application for exercise tracking and counting.
