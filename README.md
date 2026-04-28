# Spoken Digit Classification Using Advanced Digital Signal Processing

## EE 413: Applied Digital Signal Processing Project

This repository contains the implementation, analysis, and results for an audio signal classification project completed for **EE 413: Applied Digital Signal Processing**.

The project focuses on classifying spoken digits using Digital Signal Processing (DSP) feature extraction techniques and machine learning classifiers. The main goal is to compare how different signal analysis domains affect classification performance.

The project analyzes audio signals using:

**Saad Alriyan 202181050**
- Time-domain analysis

**Talal Alghamdi 202178870**
- Frequency-domain analysis using the Discrete Fourier Transform (DFT)

**Abdulrahman Alburaikan 202175630**
- Time-frequency analysis using the Short-Time Fourier Transform (STFT)

The extracted features are used to train and evaluate machine learning classifiers for spoken digit recognition.

---

## Project Title

**Spoken Digit Classification Using Advanced DSP**

---

## Project Objective

The objective of this project is to classify spoken digits from audio recordings by extracting meaningful features from speech signals using DSP techniques.

The project evaluates how well different feature extraction methods represent speech signals for machine learning classification.

The main objectives are:

- Apply DSP concepts to real-world audio signals
- Analyze speech signals in the time domain
- Analyze speech signals in the frequency domain using DFT
- Analyze speech signals in the time-frequency domain using STFT
- Extract discriminative features from spoken digit recordings
- Train machine learning classifiers using the extracted features
- Compare classifier performance across different feature extraction approaches
- Identify the most effective DSP representation for spoken digit classification
- Connect practical implementation results to theoretical DSP concepts

---

## Dataset

This project uses the **Free Spoken Digit Dataset (FSDD)**.

The Free Spoken Digit Dataset is often described as the **“MNIST of audio”** because it provides a simple and structured dataset for spoken digit classification.

### Dataset Characteristics

- Contains spoken digits from **0 to 9**
- Audio files are in **WAV format**
- Audio recordings are **mono**
- Sampling rate is approximately **8 kHz**
- Each recording is short, usually around **1 second**
- Includes multiple speakers
- Includes multiple recordings per digit
- Audio is relatively clean with little background noise
- Ground-truth labels are available from the filenames
- Suitable for DSP-based classification experiments

### Dataset Source

```text
https://github.com/Jakobovski/free-spoken-digit-dataset
