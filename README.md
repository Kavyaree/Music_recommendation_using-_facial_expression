# Music_recommendation_using-_facial_expression
# 🎵 Emotion-Based Music Recommender System

A real-time, emotion-aware music recommender system that captures facial and hand gestures via webcam, classifies your emotion using a deep learning model, and suggests music tailored to your emotional state. Built with **Streamlit**, **MediaPipe**, and a pretrained **Keras model**.

---

## 📌 Features

- 🎥 Real-time webcam-based emotion detection
- 🤖 Deep learning model for emotion classification
- 🎯 Facial and hand landmark detection using MediaPipe
- 🎵 YouTube music recommendations based on detected emotion, language, and singer preferences
- 💾 Local session handling with `emotion.npy` and `labels.npy`

---

## 🛠️ Tech Stack

| Component         | Technology         |
|------------------|--------------------|
| Web Framework     | Streamlit          |
| Video Processing  | OpenCV + WebRTC    |
| Landmark Detection| MediaPipe          |
| ML Model          | Keras (model.h5)   |
| Emotion Labels    | NumPy              |

---

## 📂 File Structure

.
├── music.py # Main Streamlit app
├── model.h5 # Pretrained emotion detection model
├── labels.npy # List of emotion labels
├── emotion.npy # Stores last predicted emotion
├── MUSIC Recommender system.ipynb # Development notebook


---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://gitlab.com/your-username/emotion-music-recommender.git
   cd emotion-music-recommender
