# NeuralScript: Handwritten Digit Recognition and OCR System

NeuralScript is an AI-powered handwritten digit recognition application built using TensorFlow, CNNs, OpenCV, EasyOCR, and Streamlit.

The project can recognize handwritten digits through multiple input methods including image uploads, live camera capture, video processing, drawing canvas input, and multi-digit OCR detection.

The CNN model is trained on the MNIST dataset and achieves approximately 99% accuracy while providing real-time predictions with confidence scores.

## Features

* Handwritten digit recognition using a Convolutional Neural Network (CNN)
* Image upload prediction (PNG, JPG, JPEG)
* Real-time camera digit recognition
* Video frame-by-frame digit analysis
* Interactive drawing canvas for handwritten digit input
* Multi-digit text recognition using EasyOCR
* Confidence score visualization
* Modern dark/light themed UI
* OpenCV-based preprocessing pipeline
* Streamlit web application interface

## Technologies Used

* Python
* TensorFlow / Keras
* Streamlit
* OpenCV
* NumPy
* EasyOCR
* Matplotlib
* PIL (Pillow)

## Dataset

The model is trained on the MNIST handwritten digit dataset containing:

* 60,000 training images
* 10,000 testing images
* 10 digit classes (0–9)
* Image size: 28×28 pixels

## Model Architecture

Input (28×28)
→ Conv2D (32 Filters)
→ MaxPooling
→ Conv2D (64 Filters)
→ MaxPooling
→ Dropout
→ Dense (128)
→ Softmax (10 Classes)

## Performance

* Test Accuracy: 99.2%
* Precision: 99.1%
* Recall: 99.2%
* F1 Score: 99.15%
* Average Inference Time: <50 ms

## Input Modes

1. Upload Image
2. Camera Capture
3. Video Analysis
4. Draw Canvas
5. Multi-Digit OCR

## Future Enhancements

* Digit segmentation for handwritten numbers
* Real-time webcam streaming prediction
* Support for alphabets and symbols
* Custom dataset training
* Model deployment on cloud platforms

Developed by Uzzair Sheikh

