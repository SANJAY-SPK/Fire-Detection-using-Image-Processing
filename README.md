# Fire Detection Using Image Processing

## Overview
This project aims to develop a fire detection system using image processing techniques. The primary objective is to identify the presence of fire in images or video feeds in real-time, enabling early detection and response to potential fire hazards.

## Features
- **Real-time Fire Detection**: Process video streams or images to detect fire in real-time.
- **High Accuracy**: Utilizes advanced image processing algorithms and machine learning models to achieve high detection accuracy.
- **Alerts and Notifications**: Sends alerts and notifications when fire is detected.
- **Scalable and Modular**: Designed to be easily integrated into existing surveillance systems or expanded with additional features.

## Requirements
- Python 3.x
- OpenCV
- NumPy
- TensorFlow / Keras (for machine learning models)
- Any other dependencies specified in `requirements.txt`

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/fire-detection-image-processing.git
    cd fire-detection-image-processing
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. **Image-based Fire Detection**:
    ```bash
    python detect_fire_image.py --image path_to_image.jpg
    ```

2. **Video-based Fire Detection**:
    ```bash
    python detect_fire_video.py --video path_to_video.mp4
    ```

3. **Real-time Fire Detection using Webcam**:
    ```bash
    python detect_fire_webcam.py
    


## Methodology
1. **Data Collection**: Gather a diverse set of images and videos containing fire and non-fire scenarios.
2. **Preprocessing**: Apply preprocessing techniques such as resizing, normalization, and augmentation to the dataset.
3. **Model Training**: Train a convolutional neural network (CNN) on the preprocessed dataset to classify images containing fire.
4. **Detection Algorithm**: Implement a detection algorithm using the trained model to process video frames in real-time.
5. **Evaluation**: Test the system on a separate validation dataset and real-world scenarios to evaluate performance.

## Results
The fire detection system achieves high accuracy on the test dataset and demonstrates reliable performance in real-time scenarios. The system is capable of detecting fire in various conditions and lighting environments.

## Future Work
- Improve the robustness of the detection algorithm under different weather conditions and occlusions.
- Integrate additional sensors (e.g., smoke detectors) to enhance detection accuracy.
- Develop a mobile application for remote monitoring and alerts.




