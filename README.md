# Emotion Recognition with Python
## Overview 
This project focuses on real-time emotion recognition using Python, TensorFlow, Keras, and OpenCV. The goal is to detect emotions like happiness, sadness, anger, confusion, and fear from live video feed through a webcam. 📹

## Features
- Trained a deep learning model using TensorFlow and Keras to recognize emotions.
- Implemented live video analysis using OpenCV and a webcam.
- Supports detection of the following emotions: happy, sad, angry, confused, and scared.

## Contents
- **train_model.ipynb**: Jupyter Notebook containing the code to train and evaluate the emotion recognition model.
- **emotion_recognition.py**: Python script to perform live emotion recognition on video using OpenCV and the trained model.
- **Facial Data/**:
  - **happy/**: Folder containing images of people displaying happiness.
  - **sad/**: Folder containing images of people displaying sadness.
  - **angry/**: Folder containing images of people displaying anger.
  - **confused/**: Folder containing images of people displaying confusion.
  - **scared/**: Folder containing images of people displaying fear.
- **requirements.txt**: List of dependencies needed to run the project.
- **haarcascade_frontalface_default.xml**: XML file used for face detection with OpenCV's cascade classifiers.
- **LICENSE**: License file.

## Usage
- Training the Model:
Open and run the **train_model.ipynb** notebook to train and evaluate the model. Ensure you have **TensorFlow** and **Keras** installed.

- Live Emotion Recognition:
Run **emotion_recognition.py** to start the live emotion recognition from your webcam.

## Installation
- Clone the repository:
```
git clone https://github.com/mariajosesalasmiranda/Emotion-Vision.git
cd Emotion-Vision
```
- Install dependencies:
```
pip install -r requirements.txt
```
## License
This project is licensed under the MIT License. It is intended for educational purposes and personal use. For any commercial use or redistribution, please refer to the terms mentioned in the license file.

## Contribution
Contributions are welcome! Feel free to open issues or pull requests for any improvements or bug fixes. 🤝

## Acknowledgments
Special thanks to [mention_any_contributors_or_references] for their valuable insights and contributions to this project.
This project was created as a simple example for learning purposes.
