# Audio Spoof Detection Model

This repository contains a Support Vector Machine (SVM)-based model designed to detect audio spoofing attacks. The model processes audio features to distinguish between genuine and spoofed audio samples, contributing to the security of voice authentication systems.

## Table of Contents

- [Requirements](#requirements)
  - [Dependencies](#dependencies)
  - [Setup Instructions](#setup-instructions)
- [Dataset](#dataset)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Requirements

To set up and run this project, ensure that your system meets the following requirements:

- **Python Version**: Python 3.x
- **Jupyter Notebook**: For running the provided notebook files.

### Dependencies

The project relies on several Python libraries. These dependencies are listed in the `requirements.txt` file included in this repository.

### Setup Instructions

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/audio-spoof-detection.git
2. **Navigate to the Project Directory**:
    ```bash
    cd audio-spoof-detection
3. **Create a Virtual Environment**(Optional)
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'
4. **Install Dependencies**
    ```bash
    pip install -r requirements.txt

5. **Obtain the Dataset**

The model requires the ASVspoof 2019 Logical Access (LA) dataset. Due to licensing restrictions, the dataset is not included in this repository. You can obtain it from the ASVspoof website. After downloading, place the dataset in the data directory within the project folder.

6. **Run the Jupyter Notebook**
    ```bash
    jupyter notebook



