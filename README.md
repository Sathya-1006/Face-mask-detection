# Face-mask-detection

This project uses a deep learning model with OpenCV and TensorFlow to detect whether people in the video feed are wearing face masks. It leverages a MobileNetV2 model for mask detection and a pre-trained deep neural network (DNN) model for face detection. This system can be used in real-time video streams, making it ideal for scenarios where monitoring mask compliance is crucial.

## Features
- **Face Detection:** Uses OpenCV’s DNN module to detect faces within the video frame.
- **Mask Detection:** Predicts if a detected face has a mask or not, displaying a label and bounding box color (green for mask, red for no mask).
- **Real-Time Processing:** Processes frames from a live video stream with minimal latency.

## Installation
1. Clone the repository and navigate to the project directory.
2. Ensure the following Python packages are installed:
   ```
   pip install tensorflow opencv-python imutils numpy
