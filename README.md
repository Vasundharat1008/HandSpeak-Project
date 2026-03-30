# HandSpeak – AI-Powered Sign Language to Speech

## Overview
HandSpeak is a machine learning project that converts hand gestures from sign language into spoken words in real-time. 
It uses Random Forest and SVM models achieving over 85% accuracy.

## Problem Statement
Many people with hearing impairments face communication barriers. This project helps by translating sign language gestures into speech.

## Tools & Technologies
- Python (NumPy, Pandas, scikit-learn)  
- Jupyter Notebook  
- Text-to-Speech (pyttsx3 or gTTS)  

## ML Workflow
1. Data preprocessing and normalization  
2. Feature extraction from hand gestures  
3. Model training: Random Forest, SVM  
4. Evaluation using confusion matrix and accuracy  
5. Real-time gesture-to-speech pipeline

## Key Achievements
- Random Forest and SVM models with >85% accuracy  
- Real-time translation of hand gestures to speech  
- Confusion matrix analysis for model evaluation

## Screenshots
- ![Confusion Matrix](screenshots/confusion_matrix.png)  
- ![Real-time Demo](screenshots/gesture_demo.png)

## How to Run
1. Install required Python packages  
2. Run `model_training.ipynb` to see training & evaluation  
3. Run `real_time_demo.py` for live gesture-to-speech conversion
