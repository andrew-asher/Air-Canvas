# Air Canvas ML Model

Ever wished to capture your imagination by just waving your finger in the air? The "Air Canvas" project allows you to draw in the air using hand gestures, leveraging OpenCV and MediaPipe for real-time hand tracking and landmark detection.

## Tools and Libraries Used

- Python3
- NumPy
- OpenCV: Essential for capturing and processing video frames.
- MediaPipe: Enables accurate and real-time hand landmark detection.

## How It Works

1. **Capture Video:** Using OpenCV, the script captures live video feed from the webcam.
2. **Process Frames:** MediaPipe processes each frame to detect and track hand landmarks.
3. **Draw Landmarks:** Detected hand landmarks are drawn on the video frames, creating a virtual canvas.

## Algorithm

- Capture frames and convert them to HSV color space.
- Prepare a canvas frame with ink buttons.
- Configure MediaPipe to detect one hand.
- Detect landmarks by passing the RGB frame to the MediaPipe hand detector.
- Track forefinger coordinates and store them in an array.
- Draw the points from the array on the frames and canvas.

## Usage

1. Clone the repository: `git clone https://github.com/your-username/air-canvas.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the script: `python air_canvas.py`


