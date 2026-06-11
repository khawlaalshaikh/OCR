# OCR: Handwritten Text Detection and Recognition

This project combines object detection and Optical Character Recognition (OCR) techniques to detect and extract handwritten text from document images. Using Faster R-CNN for text region detection and EasyOCR for character recognition, the system provides an end-to-end pipeline for handwritten text analysis.

## Overview

The project focuses on:

* Detecting handwritten text regions within images
* Extracting text using OCR techniques
* Visualizing detected text locations
* Evaluating detection performance
* Building a reproducible handwritten text recognition workflow

## Features

* Handwritten text detection using Faster R-CNN
* Optical Character Recognition with EasyOCR
* Automatic image preprocessing
* Bounding box visualization
* Model training and evaluation pipeline
* Support for handwritten document datasets

## Technologies Used

* Python
* PyTorch
* Torchvision
* OpenCV
* EasyOCR
* NumPy
* Matplotlib
* Scikit-learn

## Dataset

The project utilizes a handwriting recognition dataset containing handwritten document images. The dataset is used to train and evaluate text detection models capable of identifying handwritten regions in images.

## Workflow

1. Load and preprocess handwritten document images.
2. Train a Faster R-CNN model for text region detection.
3. Detect handwritten text locations using bounding boxes.
4. Apply OCR to recognized text regions.
5. Evaluate model performance.
6. Visualize detection and recognition results.

## Project Structure

```text
OCR/
│
├── data/
├── models/
├── notebooks/
├── results/
├── images/
├── requirements.txt
└── README.md
```

## Installation

```bash
git clone <repository-url>
cd OCR
pip install -r requirements.txt
```


## Applications

* Handwritten document digitization
* Historical document preservation
* Automated form processing
* Text extraction from scanned documents
* Document analysis systems

## Results

The system combines object detection and OCR to accurately identify handwritten text regions and convert them into machine-readable text, enabling efficient document digitization and analysis.

## Future Improvements

* Transformer-based OCR models
* Real-time handwritten text recognition
* Multi-language support
* Enhanced preprocessing techniques
* Web-based deployment

## License

MIT License
