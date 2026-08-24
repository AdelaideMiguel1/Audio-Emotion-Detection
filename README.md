# 🎙️ Audio Emotion Detection

**Audio Emotion Detection** is an AI-powered Speech Emotion Recognition (SER) project designed to identify human emotions from speech/audio recordings. 
The system processes audio signals, extracts meaningful acoustic features, and uses machine learning/deep learning techniques to classify emotions.

## 🚀 Project Overview

Human speech contains valuable emotional information such as tone, pitch, energy, and speaking patterns. This project aims to analyze these characteristics 
and automatically determine the emotional state expressed in an audio recording.

The system can be used for applications such as:

* 🎧 Emotion-aware virtual assistants
* 🤖 Human-AI interaction
* 📞 Customer service and call-center analysis
* 🧠 Sentiment and behavioral analysis
* 🎓 Educational applications
* 💬 Emotion-aware communication systems

## ✨ Key Features

* 🎤 Audio file input and processing
* 🔊 Speech signal preprocessing
* 📊 Audio feature extraction
* 🧠 Machine learning/deep learning-based emotion classification
* 😊 Detection of multiple human emotions
* 📈 Model evaluation and performance analysis
* 🔍 Visualization of audio and classification results

## 🛠️ Technologies

* Python
* Librosa
* NumPy
* Pandas
* Scikit-learn
* TensorFlow / Keras
* Matplotlib
* Machine Learning & Deep Learning


  
📈 Datasets Used
Dataset	               Samples	                    Accent	                            Speakers	                       Quality
RAVDESS	               5,252	                    US English	                       24 actors	                        Studio
TESS 	               2,800	                    Canadian English	                  2 actresses	                        Lab
Emotions  Indians	     2,843                        Indian English	                       20+ speakers	                   Conversational
Total	               10,895	                    Multi-accent	                       46+ speakers	                   Diverse

## 🔄 System Workflow

```text
Audio Input
     ↓
Audio Preprocessing
     ↓
Feature Extraction
     ↓
Feature Processing
     ↓
Trained ML/DL Model
     ↓
Emotion Classification
     ↓
Predicted Emotion
```

📊 Performance Results
Overall Metrics
Metric	               Value
Test Accuracy	          97.61%
Validation Accuracy  	97.80%
F1-Score (Macro)	     97.32%
F1-Score (Weighted)	     97.62%
Training Time       	105.5 min (GPU)


Per-Emotion Performance
Emotion	Precision	Recall	F1-Score	Support
Neutral	98.1%	100.0% ✨	99.1%	210
Calm	     90.1%	92.6%	91.3%	108
Happy	97.9%	96.2%	97.0%	289
Sad  	97.4%	97.4%	97.4%	270
Angry	97.9%	98.7%	98.3%	232
Fearful	99.6% ✨	97.4%	98.4%	228
Disgust	98.0%	98.0%	98.0%	149
Surprised	98.7%	99.3%	99.0%	149

## 🎯 Objective

The main objective of this project is to develop an intelligent system capable of recognizing emotions from human speech and demonstrating how 
artificial intelligence can be applied to understand emotional characteristics in audio data.

## 📌 Future Improvements

* Real-time emotion detection through a microphone
* Web-based emotion detection interface
* Mobile application integration
* Support for additional languages
* Improved deep learning architectures
* Real-time emotion visualization
* Integration with conversational AI systems

## 👨‍💻 Project

This project was developed as an AI/ML project exploring **Speech Emotion Recognition and Audio Signal Processing**.
