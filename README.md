# Real-Time Emotion Detection

## Overview
This project detects human emotions in real-time using facial expressions captured through a webcam, utilizing a convolutional neural network (CNN) model trained on the FER2013 dataset.

## Objectives
- Develop a real-time emotion detection system.
- Use Keras, OpenCV, and other libraries.
- Train and deploy a CNN model for emotion recognition.
- Continuously display detected emotions on live video frames.

## Installation

### Prerequisites
- Python 3.x
- pip
- Virtual environment (optional)


## Usage
Start the emotion detection application:
```bash
python realtimedetection.py
```
Ensure your webcam is connected. The application will start the live video feed and display detected emotions in real-time.

## Technologies Used
- Python
- OpenCV
- TensorFlow/Keras

## Model Training
1. Import the FER2013 dataset using Kaggle API.
2. Preprocess the data.
3. Build and train the CNN model.
4. Save the trained model.

## Real-Time Emotion Detection
1. Load the pre-trained model.
2. Capture video frames using OpenCV.
3. Detect faces and classify emotions.
4. Display emotion labels on the video feed.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- Thanks to the open-source community for providing valuable resources and tools.
- Thanks to the [FER2013 dataset](https://www.kaggle.com/datasets/msambare/fer2013) for providing the dataset used in this project.

