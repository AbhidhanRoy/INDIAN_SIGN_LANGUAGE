# Sign Bridge – Indian Sign Language (ISL) to Text/Speech Translation  

## 📌 Overview  
**Sign Bridge** is a real-time translation system designed to bridge communication gaps between the hearing and speech-impaired community and the general public. The project translates **Indian Sign Language (ISL) gestures into text and speech** and also provides reverse translation (**text/speech to ISL animations**).  

This project was developed as part of **Smart India Hackathon 2024 (Team ID: 11330 | Idea ID: 15865)**.  

---

## 🎯 Objectives  
- Enable seamless communication between ISL users and non-ISL speakers.  
- Provide **real-time gesture recognition** using computer vision and deep learning.  
- Support **bi-directional translation** (ISL ➝ Text/Speech and Text/Speech ➝ ISL).  
- Enhance inclusivity by integrating with daily communication platforms.  

---

## 🛠️ Features  
- **ISL ➝ Text & Speech:** Recognizes ISL gestures from live video and translates them into text and speech.  
- **Text/Speech ➝ ISL:** Converts spoken or typed input into ISL animations/videos.  
- **Facial Expression Recognition:** Captures emotional tone to provide context.  
- **Multi-Language Speech Support:** Generates translations in multiple Indian and global languages.  
- **Crowd-Sourced Data Collection:** Allows users to contribute gestures for dataset growth.  
- **Integration with Communication Tools:** Compatible with Zoom, Microsoft Teams, and Slack for real-time group translation.  

---

## 🧑‍💻 Tech Stack  
- **Frontend:** Flutter, Dart  
- **Backend:** Flask, Python  
- **Database:** PostgreSQL, MongoDB  
- **AI/ML Models:** TensorFlow/Keras, MediaPipe, OpenCV, NLP  
- **Speech Processing:** gTTS, SpeechRecognition  
- **Cloud & APIs:** Google Cloud, REST APIs  

---

## 📂 Project Structure  
SignBridge/
│── dataset/ # ISL gesture video dataset
│── models/ # Trained deep learning models
│── backend/ # Flask backend services
│── frontend/ # Flutter mobile & web app
│── utils/ # Helper scripts
│── docs/ # Documentation & reports
│── README.md # Project documentation


---

## 🚀 Getting Started  

### Prerequisites  
- Python 3.8+  
- Flutter SDK  
- PostgreSQL/MongoDB installed  

### Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/signbridge.git
   cd signbridge

### Set up backend environment:


- cd backend
- pip install -r requirements.txt
- Start backend server:
- python app.py
- Run Flutter frontend:
- cd frontend
- flutter run


## 📊 Enhancements & Future Work
Improve ISL gesture dataset with community contributions.

Add support for real-time group translations in video conferences.

Expand to support other sign languages (ASL, BSL, etc.).

Deploy as a cross-platform mobile & web application with cloud scalability.
