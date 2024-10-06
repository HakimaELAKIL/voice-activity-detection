"# voice-activity-detection" 

# Voice Activity Detection (VAD)

This repository contains code and models for Voice Activity Detection (VAD) using deep learning techniques. The goal of the project is to accurately detect speech in noisy environments using advanced signal processing methods and machine learning models like CNNs and LSTMs.

## Features
- Voice Activity Detection based on audio features such as MFCC, energy, and spectral flux.
- Models trained using convolutional neural networks (CNNs) and Long Short-Term Memory networks (LSTMs).
- Robust to noisy environments with the use of noise reduction techniques.
  
## Project Structure
- `lstmm.ipynb`: Notebook for training and evaluating LSTM-based VAD models.
- `Bilstm.h5`, `GRU.h5`: Pretrained models used for VAD.
- `Audio/`: Folder containing audio files used for training and evaluation.
- `CSV/`: Folder with CSV files containing extracted audio features.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/HakimaELAKIL/voice-activity-detection.git

