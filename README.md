# Audio Emotion Recognition

A Machine Learning project to recognize human emotions from speech using audio features.

This app takes a ".wav" file as input, extracts MFCC features, and predicts emotions like "angry, happy, sad, neutral".  
It comes with a simple **Streamlit web interface** for live testing.

---

## Features
- Train an **SVM model** on speech audio
- Upload audio files and get real-time predictions
- Uses Librosa for audio preprocessing
- Web app built with Streamlit

---


## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/audio-emotion-recognition.git
cd audio-emotion-recognition
pip install -r requirements.txt
