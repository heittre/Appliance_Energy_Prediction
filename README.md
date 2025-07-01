# LSTM Energy Use Prediction Project

This repository contains a machine learning project to predict `Appliances` energy use using a Long Short-Term Memory (LSTM) neural network. The project compares the LSTM model against a baseline (mean prediction) and includes data preprocessing, model training, and evaluation.

## Overview
- **Dataset**: Energy consumption data (e.g., `energy_data.csv`) with features like `Appliances`, `T1`, `lights`, `Hour`, etc.
- **Model**: LSTM implemented with TensorFlow/Keras to leverage time-series patterns, including lagged `Appliances` as a feature.
- **Baseline**: Mean prediction of `Appliances` for comparison.
- **Environment**: Developed and tested in Google Colab.

## Prerequisites
To run this project, ensure you have the following:
- **Google Colab Account**: Access to Google Colab for running the notebook.
- **Python Libraries**: The notebook uses standard libraries that are pre-installed in Colab, including:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `tensorflow`
  - `sklearn`
- **Data File**: The dataset `energy_data.csv` must be uploaded to Colab or linked via Google Drive.

## How to Run the Project
Follow these steps to replicate the project in Google Colab:

1. **Clone or Download the Repository**:
   - Clone this repository to your local machine or download the ZIP file from GitHub.
   - Upload the `LSTM_Energy_Prediction.ipynb` notebook (or the equivalent file name) to Google Colab.

2. **Set Up Google Colab**:
   - Open Google Colab (https://colab.research.google.com/).
   - Upload the notebook file by clicking "File > Upload notebook" or drag and drop it.

3. **Upload the Dataset**:
   - In Colab, click the folder icon on the left sidebar.
   - Upload `energy_data.csv` by clicking the upload arrow or mount your Google Drive (see Step 4) and copy the file there.
   - If using Drive, mount it with:
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
