# Real Time Face Emotion Detection Application

This application performs real-time face emotion detection using OpenCV, a custom CNN model, and Streamlit. It allows users to detect emotions through their webcam feed and displays the recognized emotions while saving the predictions into a CSV file.

## Features

- **Webcam Face Detection**: Utilizes the webcam feed for real-time face detection.
- **Real-Time Emotion Recognition**: Recognizes emotions from detected faces in real-time.
- **Prediction Storage**: Saves recognized emotions into a CSV file for further analysis.

## Demo

Provide some visuals or GIFs demonstrating how the application works. This section helps users quickly understand what your application does and how they can interact with it.

## Installation

To run this application locally, follow these steps:

1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Ensure you have the necessary model and cascade classifiers files (e.g., `emotion_model1.json`, `emotion_model1.h5`, `haarcascade_frontalface_default.xml`) in the appropriate paths.

## Usage

To run the application, execute the following command:

```bash
streamlit run app.py
