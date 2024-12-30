# Face Emotion Recognition Using DeepFace and TensorFlow
## Overview 
This project contains two implementations of a face emotion recognition system using two different approaches:
1. **DeepFace**: A high-level library for deep learning-based face analysis.
2. **TensorFlow** and **FER-2013 dataset**: A custom model built using TensorFlow and trained on the FER-2013 dataset.
Both implementations include a live demo using **OpenCV** to detect and classify emotions in real-time from webcam input.

## Getting Started 
### Contents
- ```deepface_fer.ipynb```: Jupyter notebook using DeepFace for emotion recognition.
- ```tensorflow_fer.ipynb```: Jupyter notebook using TensorFlow with a custom-trained model on the FER-2013 dataset.
- ```emotion_recognition_model.h5```: Trained model file for the TensorFlow approach.
- ```haarcascade_frontalface_default.xml```: Haar Cascade classifier for face detection.
- ```happy.jpg```, ```sad.jpg```, ```surprise.jpeg```: Sample images for testing emotion recognition.
- ```requirements.txt```: List of Python dependencies required to run the project.
- ```LICENSE```: The license for this project.

### Installation
1. Clone the repository:
```
git clone https://github.com/mariajosesalasmiranda/Emotion-Vision.git
cd Emotion-Vision
```
2. Install dependencies:
```
pip install -r requirements.txt
```
Alternatively, you can install the individual packages manually:
```
pip install tensorflow deepface opencv-python numpy matplotlib
```
3. Download the FER-2013 dataset
The FER-2013 dataset is required for the TensorFlow-based emotion recognition model. You can download the dataset from [Kaggle](!https://www.kaggle.com/datasets/msambare/fer2013)
4.  Download Haar Cascade XML for face detection
The ```haarcascade_frontalface_default.xml``` file is required for face detection using OpenCV. You can download it from the official [OpenCV repository](!https://github.com/kipr/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml).

### Usage
1. Run the Notebooks
You can run the notebooks directly in **VS Code** or any other Jupyter notebook environment.
    - For DeepFace-based emotion recognition, open and ```run deepface_fer.ipynb```
    - For the TensorFlow-based emotion recognition, open and run ```tensorflow_fer.ipynb```
2. Live Demo
Both implementations include a live demo that uses OpenCV to capture video from your webcam, detect faces, and predict the emotion. 
To run the demo, simply execute the corresponding notebook and follow the instructions inside the cells.

3. Model Files
The ```emotion_recognition_model.h5``` file is the trained model used in the TensorFlow-based approach. You don't need to train it again; simply load the model in the notebook to start using it.

4. Sample Images
You can use the sample images (```happy.jpg```, ```sad.jpg```, ```surprise.jpeg```) to test the emotion recognition model. 
The images can be loaded into the notebooks to see how the models classify emotions in pre-captured images.

## License 
This project is licensed under the MIT License. It is intended for educational purposes and personal use. For any commercial use or redistribution, please refer to the terms mentioned in the license file.

## Acknowledgments
- [Kaggle](!https://www.kaggle.com/)
- [DeepLearning_by_PhDScholar](!https://www.youtube.com/@deeplearning_by_phdscholar6925)
- [Challenges in representation learning: A report on three machine learning contests](!https://www.sciencedirect.com/science/article/abs/pii/S0893608014002159)
- [Human Emotion Recognition: Review of Sensors and Methods](!https://www.mdpi.com/1424-8220/20/3/592)
---

> [!Note]
>  This repository is primarily for educational purposes
