**👁️‍🗨️ Object Detection Assistant for Blind Persons **

This project is an AI-powered assistive system designed to help **visually impaired individuals** navigate their environment by detecting nearby objects and announcing them aloud. The system also provides **real-time date, time, and location** details using speech synthesis, making it a smart companion for the blind.


**📌 Features**

- 🎯 **Real-time Object Detection** using computer vision.
- 🔊 **Voice Announcements** of detected objects via text-to-speech.
- 🕒 Announces the **current date and time**.
- 📍 Provides the **current location** using GPS or IP geolocation.
- 🗣️ **Voice Command Activation**: Start/stop detection using simple voice commands (e.g., "start detection", "stop detection").

**🧠 Technologies Used**

- **Python**
- **OpenCV** – Camera access and frame processing
- **YOLOv5** – For object detection
- **SpeechRecognition** – For voice commands
- **datetime module** – For current date and time


** 🛠️ How It Works **

1. The system starts when the user gives a voice command like **"start detection"**.
2. The camera captures real-time video, and the system detects and recognizes objects in front of the user.
3. Detected object names are announced via audio (e.g., "Person ahead", "Car on the right").
4. When the user says **"tell me the date and time"**, the system speaks the current date and time.
5. On saying **"where am I"**, the system announces the approximate location (city, area).
6. Detection can be stopped using the voice command **"stop detection"**.

**🚀 Installation**

git clone (githubpath)
cd object-detection-blind-assist
