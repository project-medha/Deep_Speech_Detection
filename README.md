# Audio Classification Project: Real vs Fake Detection

## Project Description
This project focuses on detecting fake audio samples using machine learning techniques. The model uses audio features like MFCCs, chroma, and spectral properties to classify audio clips as either "real" or "fake."

## Features Extracted
- MFCC (Mel-Frequency Cepstral Coefficients)
- Chroma
- Spectral Centroid
- Spectral Bandwidth
- Spectral Rolloff
- Zero Crossing Rate

## Technologies Used
- Python
- TensorFlow
- Librosa
- Scikit-learn
- Pandas
- NumPy

## Dataset
- **Real Audio Samples**: Located in the `REAL` folder.
- **Fake Audio Samples**: Located in the `FAKE` folder.

## How to Use
### 1. Prerequisites
Ensure you have Python 3.8+ installed along with the required libraries. Use the provided `requirements.txt` file to install dependencies.

### 2. Running the Notebook
1. Place the dataset in the specified folders:
   - Real: `REAL`
   - Fake: `FAKE`
2. Open the notebook (`df_librosa_ver2.ipynb`) in Jupyter Notebook or VS Code.
3. Execute the cells step-by-step to:
   - Extract features from the dataset.
   - Train the machine learning model.
   - Test and evaluate the model.

### 3. Output
The notebook will output:
- Model performance metrics (accuracy, precision, recall).
- Predictions for audio clips.


