# Digits Classification using TensorFlow and scikit-learn
This repository contains code for classifying digits from the classic Digits dataset using TensorFlow and scikit-learn. The project involves image processing, feature extraction, model training, and evaluation.

## Project Overview
The project includes three main approaches to feature extraction from digit images:

* Image Moments: Extract statistical moments of contours in the images.
* Bounding Rectangles: Extract bounding rectangle properties of contours.
* Combined Moments and Rectangles: Extract both moments and bounding rectangle properties.

A neural network model is used to classify the digits based on these features.

## Files
* image_processing_code.py: Contains the code for feature extraction, model training, and evaluation. This file includes three versions of the code demonstrating different feature extraction methods.

## Features
* Image Moments: Statistical moments derived from contours in the images.
* Bounding Rectangles: Properties of bounding rectangles around contours.
* Combined Features: A combination of moments and bounding rectangle properties.
  
## Requirements
* Python 3.x
* TensorFlow
* scikit-learn
* OpenCV
* Pandas
* NumPy
* Matplotlib
* Seaborn
  
### Install the required packages using pip:
pip install tensorflow scikit-learn opencv-python pandas numpy matplotlib seaborn

## Usage

#### 1. Feature Extraction:
  * Image Moments: Extracts moments of contours.
  * Bounding Rectangles: Extracts bounding rectangle properties.
  * Combined Features: Extracts both moments and bounding rectangle properties.
  
#### 2. Model Training:
  * A neural network is trained using the extracted features.
  * The model architecture includes an input layer, a flatten layer, and two dense layers.

#### 3. Evaluation:
  * The model is evaluated on a test set.
  * Metrics such as accuracy, precision, recall, and F1-score are computed.
  * A confusion matrix is plotted to visualize classification results.
  
## Example Output
The code will produce:

* Test accuracy of the model.
* A confusion matrix plot.
* Metrics including precision, recall, and F1-score.

## Notes
Ensure you run each code cell separately if using a notebook environment.
