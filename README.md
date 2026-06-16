# Face Mask Detection Using Deep Learning

## Overview

This project uses a Convolutional Neural Network (CNN) to detect whether a person is wearing a face mask or not. The model is trained on image data and performs binary classification: With Mask and Without Mask.

## Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

## Features

- Image preprocessing
- Data normalization
- CNN model training
- Model evaluation
- Face mask prediction

## Model Architecture

- Conv2D Layer
- MaxPooling2D Layer
- Conv2D Layer
- MaxPooling2D Layer
- Flatten Layer
- Dropout Layer
- Dense Layer
- Output Layer (Softmax)

## Dataset

The dataset contains two classes:

- With Mask
- Without Mask

## Installation

```bash
pip install -r requirements.txt
```

## Usage

1. Open the notebook file.
2. Run all cells sequentially.
3. Train the CNN model.
4. Test predictions on sample images.

## Project Structure

```text
Face-Mask-Detection/
│
├── Face_Mask_Detection.ipynb
├── README.md
└── requirements.txt
```

## Future Improvements

- Real-time webcam detection
- Transfer Learning with MobileNetV2
- Web application deployment
- Improved accuracy using larger datasets

## Author

Mubeena pk
