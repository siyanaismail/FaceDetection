# Real-Time Face Detection with OpenCV

This is a simple Python project that uses OpenCV and Haarcascade classifiers to detect faces in real-time through your webcam.

## Features

- Real-time face detection using your computer's webcam
- Rectangle bounding boxes drawn around detected faces
- Uses OpenCV’s built-in `haarcascade_frontalface_default.xml` model

## Requirements

Make sure the following packages are installed:

- Python 3.x
- OpenCV

You can install OpenCV using pip:

```bash
pip install opencv-python
```

## Project Structure

```text
face_detection_project/
│
├── facedetect.py        # Main Python script
├── README.md            # Project documentation
```

## How to Run

1. **Clone or Download** the repository:
   ```bash
   git clone https://github.com/yourusername/face-detection-opencv.git
   cd face-detection-opencv
   ```

2. **Run the script**:
   ```bash
   python facedetect.py
   ```

3. **Usage**:
   - The webcam window will open.
   - A green rectangle will highlight detected faces.
   - Press `Esc` (Escape key) to exit the webcam window.

## Sample Output

> A live webcam feed with green boxes drawn around faces.
