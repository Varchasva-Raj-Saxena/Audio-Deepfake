# Audio Spoof Detection using SVM

This repository contains a Jupyter Notebook that implements an SVM-based classifier for detecting spoofed versus genuine audio. The model leverages feature extraction (MFCCs, CQCCs) from the ASVspoof2019 Logical Access (LA) dataset and uses a Support Vector Machine (SVM) to classify audio samples.

## Table of Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Setup Instructions](#setup-instructions)
- [Dataset](#dataset)
- [Running the Notebook](#Running-the-Notebook)

## Overview

This project demonstrates a machine learning pipeline for audio spoof detection. The pipeline includes:
- Preprocessing raw audio data (downsampling and converting to mono)
- Extracting spectral features (MFCCs, CQCCs) using Librosa
- Training an SVM classifier with an RBF kernel
- Evaluating the model using accuracy, confusion matrix, and other metrics


## Requirements

- **Python 3.x**
- **Jupyter Notebook** (for running the notebook)

### Dependencies

The project requires the following Python libraries:
- `numpy`
- `librosa`
- `soundfile`
- `scikit-learn`

All dependencies are listed in the `requirements.txt` file.

## Setup Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/audio-spoof-detection.git
   cd audio-spoof-detection
2. **Create a Virtual Environment (optional):**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
3. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt

## Dataset
This project uses the ASVspoof 2019 Logical Access (LA) dataset.

- `Visit the ASVspoof website: https://www.kaggle.com/datasets/awsaf49/asvpoof-2019-dataset`

Download the ASVspoof 2019 LA dataset.

Unzip and organize the dataset, Keep only the LA folder and give its path.


    LA/LA/
    ├── ASVspoof2019_LA_train/
    ├── ASVspoof2019_LA_dev/
    └── ASVspoof2019_LA_cm_protocols/


## Running the Notebook
1. **Launch Jupyter Notebook**

    ```bash
    jupyter notebook

2. **Open main.ipynb**

    In the Jupyter interface, open the main.ipynb notebook.

3. **Execute All Cells**

    Follow the step-by-step instructions in the notebook to preprocess data, train the SVM model, and evaluate its performance.
