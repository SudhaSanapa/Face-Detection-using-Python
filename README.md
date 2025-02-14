# Face Detection using OpenCV

## Overview

This project is a simple real-time face detection application using OpenCV's Haar Cascade classifier. It captures video from the webcam and detects faces in real time, drawing green rectangles around detected faces.

## Prerequisites

Make sure you have the following installed:

- Python (>=3.x)
- OpenCV

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/SudhaSanapa/face-detection-opencv.git
   cd face-detection-opencv
   ```

2. Install dependencies:

   ```bash
   pip install opencv-python
   ```

3. Download the Haar Cascade XML file:

   - You can download it from [OpenCV GitHub](https://github.com/opencv/opencv/tree/master/data/haarcascades)
   - Place `haarcascade_frontalface_default.xml` in the same directory as the script.

## Usage

Run the script using:

```bash
python face_detection.py
```

Press `a` to exit the application.

## Code Explanation

- The script initializes the webcam.
- It loads the Haar Cascade classifier.
- It captures frames from the webcam and converts them to grayscale.
- It detects faces and draws green rectangles around them.
- Pressing the `a` key exits the application.

## Output

The application opens a window displaying the real-time video feed with detected faces highlighted.

## License

This project is open-source free to use.


