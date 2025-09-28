# emotion-recognition-using-speech
# 🎤 Speech Emotion Recognition

This project implements a **Speech Emotion Recognition (SER) System** that predicts the emotional state of a speaker from audio input.  
It combines **classical machine learning models** and a **deep learning CNN model** trained on extracted speech features, and provides a **Streamlit-based web app** for easy use.

---

## 🚀 Features

- 🎧 **Audio Preprocessing**  
  - Converts to mono, resamples (16 kHz), trims silence, normalizes audio.

- 📊 **Feature Extraction**  
  - MFCCs (Mel-Frequency Cepstral Coefficients)  
  - Chroma Features  
  - Spectral Contrast, Zero-Crossing Rate, Energy

- 🤖 **Models Implemented**  
  - Random Forest Classifier  
  - Logistic Regression  
  - CNN on Mel-Spectrograms  
  - Consensus prediction across models

- 📈 **Visualizations in App**  
  - Waveform  
  - Mel-Spectrogram  
  - Feature Importance (Random Forest)  
  - Probability distributions

- 🌐 **Deployment**  
  - End-to-end Streamlit application  
  - Upload audio and get instant predictions  
  - Download results as CSV

---

## 🛠️ Tech Stack

- **Languages & Frameworks:** Python, Streamlit, TensorFlow/Keras, scikit-learn  
- **Audio Processing:** Librosa, Soundfile  
- **Visualization:** Matplotlib, Seaborn, Plotly  
- **Deployment:** Streamlit Cloud  

---

## 📂 Repository Structure
emotion-recognition-using-speech/
│── data/ # (optional) sample audio files
│── models/ # saved ML/CNN models, encoders, scalers
│── preprocessing/ # audio preprocessing scripts
│── feature_extraction/ # MFCC, Chroma, Spectrogram extraction
│── app/ # Streamlit application
│── utils/ # helper functions
│── requirements.txt # dependencies
│── README.md # project documentation

---
##🌐 Live Demo

Try the deployed app here 👉
[Speech Emotion Recognition App](https://ankitkumarnath-emotion-recognition-using-speech-app-bpf6zt.streamlit.app/)


---
##📊 Example Outputs
Upload Audio & Get Prediction

Predicted Emotion with Confidence Scores

Waveform & Spectrogram Visualization



<img width="1440" height="900" alt="Screenshot 2025-09-29 at 12 28 41 AM" src="https://github.com/user-attachments/assets/a96d80cc-9cad-46b2-ba28-e932a34ebea2" />
<img width="1440" height="900" alt="Screenshot 2025-09-29 at 12 28 51 AM" src="https://github.com/user-attachments/assets/d1b710b5-aa44-4e44-a179-a142a3b12ca6" />
<img width="1440" height="900" alt="Screenshot 2025-09-29 at 12 29 01 AM" src="https://github.com/user-attachments/assets/f2824db9-bb15-45af-9e6b-8add7e990858" />
<img width="1440" height="900" alt="Screenshot 2025-09-29 at 12 29 09 AM" src="https://github.com/user-attachments/assets/da042b30-b4bc-4bc4-bbff-8092c9425312" />
<img width="1440" height="900" alt="Screenshot 2025-09-29 at 12 29 18 AM" src="https://github.com/user-attachments/assets/8fe94e28-3211-4bb1-92b6-756ad02051a0" />
