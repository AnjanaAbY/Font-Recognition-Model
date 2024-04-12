# Font Recognition Model and Text Extraction

This project implements a font recognition system using deep learning and extracts text from images using optical character recognition (OCR).

## Overview

The project consists of two main parts:

### 1.Font Recognition:

Uses transfer learning with the VGG16 model to classify fonts into predefined classes.
The model is trained on a dataset containing images of different fonts.
The trained model can predict the font of a given input image.

### 2.Text Extraction:

Uses the Tesseract OCR engine to extract text from images.
The extracted text can be used for further analysis or processing.

## Usage

### Font Recognition:

To train the font recognition model, run the train_model.py script.
Ensure that the dataset is organized in the specified directory structure.

### Text Extraction:

Install the required dependencies (tesseract-ocr and pytesseract).
Use the image_to_string method from pytesseract to extract text from images.

## Installation 

### 1. Install the required dependencies

!sudo apt install tesseract-ocr
!pip install pytesseract

### 2.Run the scripts:

Use train_model.py to train the font recognition model.
Use detect_font.py to predict the font of an image.
Use extract_text.py to extract text from an image.

## Credits

Font Recognition model based on VGG16: Keras Applications
Text Extraction using Tesseract OCR: Pytesseract
