📌 Overview
Speech disorders, such as stuttering, affect millions of people worldwide. This project aims to detect stuttering in speech using machine learning techniques. The model analyzes audio files, extracts key speech features, and predicts whether the speech is fluent or contains stuttering patterns.

🚀 Features
Audio Feature Extraction: Uses MFCCs, spectral centroid, and zero-crossing rate to analyze speech.
Machine Learning Model: Trains a Random Forest Classifier to distinguish between fluent and stuttered speech.
Scalability: Supports training with multiple audio files and labels.
Real-time Predictions: Predicts speech fluency and provides personalized recommendations.
Model Persistence: Save and load trained models for future use.
🛠️ Technologies Used
Python
Librosa (for audio processing)
Scikit-learn (for machine learning)
NumPy (for numerical operations)
Pickle (for model storage)

📖 Future Enhancements
Improve model accuracy with deep learning techniques (e.g., CNNs, RNNs).
Build a real-time speech analysis application.
Expand dataset for better generalization.
