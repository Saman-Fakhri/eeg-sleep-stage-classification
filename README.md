# EEG Sleep Stage Classification

EEG sleep stage classification project using MNE-Python and machine learning on the Sleep-EDF dataset.

## Overview

This project demonstrates an end-to-end EEG signal processing pipeline for sleep-stage analysis.

The workflow includes:
- EEG preprocessing
- signal filtering
- epoch segmentation
- feature extraction
- machine learning classification

## Dataset

Dataset used:
- Sleep-EDF Expanded Dataset from PhysioNet

Dataset source:
https://physionet.org/content/sleep-edfx/1.0.0/

## Technologies Used

- Python
- MNE-Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Pipeline

### 1. EEG Loading
EDF EEG recordings were loaded using MNE-Python.

### 2. Preprocessing
Applied EEG bandpass filtering between:

0.5 Hz – 30 Hz

### 3. Epoching
EEG signals were segmented into 30-second epochs.

### 4. Feature Extraction
Extracted statistical EEG features including:
- mean
- variance
- maximum amplitude

### 5. Machine Learning
Trained a Random Forest classifier using extracted EEG features.

## Results

Successfully built a complete EEG preprocessing and ML pipeline for sleep-stage analysis.

## Future Improvements

- Use real hypnogram sleep labels
- Extract spectral bandpower features
- Improve classification accuracy
- Apply deep learning models (CNN/LSTM)
- Real-time EEG analysis

## Author

Saman Fakhri
