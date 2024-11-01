# Face-mask-detection
This project uses a deep learning model with OpenCV and TensorFlow to detect whether people in the video feed are wearing face masks. It leverages a MobileNetV2 model for mask detection and a pre-trained deep neural network (DNN) model for face detection. This system can be used in real-time video streams, making it ideal for scenarios where monitoring mask compliance is crucial.

Features
Face Detection: Uses OpenCV's DNN module to detect faces within the video frame.
Mask Detection: Predicts if a detected face has a mask or not, displaying a label and bounding box color (green for mask, red for no mask).
Real-Time Processing: Processes frames from a live video stream with minimal latency.
Installation
Clone the repository and navigate to the project directory.
Ensure the following Python packages are installed:
bash
Copy code
pip install tensorflow opencv-python imutils numpy
Download the face detector model files (deploy.prototxt and res10_300x300_ssd_iter_140000.caffemodel) and place them in a face_detector directory.
Usage
Load the mask_detector.model, a pre-trained Keras model for mask detection.
Run the detect_and_predict_mask function for real-time face and mask detection.
Press q to quit the video stream.
