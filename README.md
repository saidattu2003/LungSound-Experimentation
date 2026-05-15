# LungSound Classification Experiments

## Overview

This repository contains a collection of machine learning and deep learning experiments for audio classification. The project focuses on preprocessing audio data, extracting meaningful features, training multiple classification models, and evaluating their performance.

The notebook includes:

* Audio preprocessing and augmentation
* Feature extraction from audio signals
* Traditional machine learning models
* Deep learning models using TensorFlow/Keras
* Performance evaluation and comparison

## Project Structure

```text
.
├── main.ipynb          # Main experimentation notebook
├── data/               # Dataset directory (should change in the main.ipynb paths)
├── models/             # Saved model files (optional)
├── outputs/            # Evaluation outputs and plots (optional)
└── README.md           # Project documentation
```

## Features

### Data Processing

* Audio loading and preprocessing
* Label encoding
* Dataset preparation and splitting
* Data augmentation techniques

### Feature Extraction

The notebook extracts features from audio files using libraries such as:

* Librosa
* NumPy
* Pandas

### Implemented Models

The following models are implemented and evaluated:

1. Support Vector Machine (SVM)
2. Naive Bayes Classifier
3. K-Nearest Neighbors (KNN)
4. Decision Tree Classifier
5. 1D Convolutional Neural Network (1D CNN)

### Libraries

* TensorFlow / Keras
* Scikit-learn
* Librosa
* NumPy
* Pandas
* Matplotlib

## Workflow

The experimentation pipeline follows these steps:

1. Load audio dataset
2. Perform preprocessing and augmentation
3. Extract audio features
4. Split dataset into training and testing sets
5. Train multiple machine learning models
6. Train deep learning model (1D CNN)
7. Evaluate and compare performance

## Evaluation Metrics

The models are evaluated using:

* Accuracy
* Confusion Matrix
* Classification Report

## Results

The following results were obtained from the experimentation process:

| Model         | Accuracy |
| ------------- | -------- |
| SVM           | 87.66%   |
| Naive Bayes   | 74.95%   |
| KNN           | 86.75%   |
| Decision Tree | 85.84%   |
| 1D CNN        | **88.57% **  |

According to the experiments performed in the notebook, the 1D CNN model achieved the best overall performance compared to the traditional machine learning models.


## Future Improvements

Possible future enhancements include:

* Hyperparameter tuning
* Additional deep learning architectures
* More advanced audio augmentation techniques
* Cross-validation experiments
* Model deployment


## License

This project is intended for educational and research purposes.

## Author

S.Sai Dattu
24AI60R34
