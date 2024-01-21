# Emotion Recognition with Python
## Overview 

> [!Note]
> This project was created as a simple example for learning purposes.

## Description 
The project has two main parts:
1. Training, loading and testing an emotion recognition model using TensorFlow and Keras
2. Applying the model to real-time video from a webcam using OpenCV

The model is a deep neural network trained on the FER-2013 emotion dataset. It achieves 65% validation accuracy in recognizing the emotions. The real-time
emotion recognition system captures video from a webcam, extracts faces using OpenCV, predicts the emotion using the trained model, and displays it
overlayed on top of the video frame. 

## Getting Started 
### Contents
- **train_model.ipynb**: Jupyter Notebook containing the code to train and evaluate the emotion recognition model.
- **emotion_recognition.py**: Python script to perform live emotion recognition on video using OpenCV and the trained model.
- **requirements.txt**: List of dependencies needed to run the project, which are:
  - OpenCV
  - TensorFLow
  - Numpy
  - MatplotLib  
- **happy.jpeg**: Example image for analysis. sentiment
- **haarcascade_frontalface_default.xml**: XML file used for face detection with OpenCV's cascade classifiers.
- **LICENSE**: License file.

### Depencies
- OpenCV
- TensorFlow 2.15.0
- Numpy
- Matplotlib

### Installation
- Clone the repository:
```
git clone https://github.com/mariajosesalasmiranda/Emotion-Vision.git
cd Emotion-Vision
```
- Install dependencies:
```
pip install -r requirements.txt
```
### Usage
- Training the Model:
Open and run the **train_model.ipynb** notebook to train and evaluate the model. Ensure you have **TensorFlow** and **Keras** installed.

- Live Emotion Recognition:
Run **emotion_recognition.py** to start the live emotion recognition from your webcam.

## License 
This project is licensed under the MIT License. It is intended for educational purposes and personal use. For any commercial use or redistribution, please refer to the terms mentioned in the license file.

## Contribution 
Contributions are welcome! Feel free to open issues or pull requests for any improvements or bug fixes. 

## Acknowledgments 
Special thanks to [mention_any_contributors_or_references] for their valuable insights and contributions to this project.
