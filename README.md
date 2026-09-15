# Sign Language to Text and Speech Conversion

## Overview
This project is a real-time Sign Language Recognition system that converts hand gestures into text and speech using Computer Vision and Deep Learning. It helps bridge communication between hearing-impaired individuals and others by recognizing sign language gestures through a webcam.

## Features
- Real-time hand gesture recognition
- Converts sign language gestures into text
- Text-to-speech conversion
- Deep Learning based prediction model
- Webcam-based interaction
- Supports alphabet gesture recognition (A–Z)

## Technologies Used
- Python
- OpenCV
- TensorFlow / Keras
- NumPy
- Deep Learning (CNN)

## Project Structure

```
Sign-Language-To-Text-and-Speech-Conversion
│
├── AtoZ_3.1/                 # Dataset images
├── cnn8grps_rad1_model.h5    # Trained CNN model
├── data_collection_binary.py
├── data_collection_final.py
├── final_pred.py             # Main prediction script
├── prediction_wo_gui.py
└── white.jpg
```

## Dataset
The project uses hand gesture images representing sign language alphabets (A–Z) for training and prediction.

## How It Works
1. Capture hand gestures using a webcam.
2. Process images using OpenCV.
3. Extract hand gesture features.
4. Predict the corresponding alphabet using the trained CNN model.
5. Convert the predicted text into speech.

## Installation

### Clone the Repository

```bash
git clone https://github.com/thanvitha14/sign-language-recognition.git
cd sign-language-recognition
```

### Install Dependencies

```bash
pip install opencv-python
pip install tensorflow
pip install numpy
```

Or:

```bash
pip install -r requirements.txt
```

## Run the Project

```bash
python final_pred.py
```

## Applications
- Assistive technology for hearing-impaired individuals
- Educational sign language learning tools
- Human-computer interaction systems

## Future Enhancements
- Support for words and sentences
- Improved gesture accuracy
- Multi-language speech output
- Mobile application integration

## Author
Developed as an academic Deep Learning and Computer Vision project for Sign Language Recognition.
