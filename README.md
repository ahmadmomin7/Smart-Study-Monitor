# 🚀 Smart Study Monitor

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=25&pause=1000&color=00C2FF&center=true&vCenter=true&width=600&lines=Welcome+to+Smart+Study+Monitor!;Stay+Awake.+Stay+Focused.;AI-Powered+Study+Assistant+%F0%9F%A7%A0" alt="Animated project introduction" />

**An AI-powered study assistant that helps you stay focused using real-time computer vision.**

</div>

---

## 💡 About the Project

Smart Study Monitor is a Python-based computer vision application that monitors your study sessions using a webcam. It detects sleepiness, face covering, and mobile phone usage, then alerts you with audio warnings.

## ✨ Features

- 😴 **Sleep Detection** — Detects prolonged eye closure using facial landmarks.
- 👀 **Face Cover Detection** — Alerts when your face disappears from the camera view.
- 📱 **Phone Detection** — Detects mobile phones using YOLOv8.
- 🔊 **Audio Alerts** — Plays different sounds for different distractions.
- 🎥 **Live Monitoring** — Displays real-time webcam video and detection warnings.

## 🛠️ Tech Stack

<div align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV" />
<img src="https://img.shields.io/badge/YOLOv8-111F68?style=for-the-badge&logoColor=white" alt="YOLOv8" />
<img src="https://img.shields.io/badge/MediaPipe-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="MediaPipe" />
<img src="https://img.shields.io/badge/Pygame-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Pygame" />

</div>

## ⚙️ Installation

**1. Clone the repository**

```bash
git clone https://github.com/ahmadmomin7/Smart-Study-Monitor.git
cd Smart-Study-Monitor
```

**2. Install dependencies**

```bash
python -m pip install -r requirements.txt
```

**3. Prepare the audio files**

Place these files beside `app.py`:

- `alarm.mp3`
- `faudio.mp3`
- `paudio.mp3`

**4. Run the application**

```bash
python app.py
```

The YOLO model may download automatically on its first run. A webcam and compatible Python environment are required.

## 🔍 How It Works

```text
Webcam Input
     |
     v
Face Mesh + Eye Analysis
     |
     +----> Sleepiness Detection
     |
     +----> Face Visibility Detection
     |
     v
YOLOv8 Phone Detection
     |
     v
Warning Messages + Audio Alerts
```

## 🎯 Project Goal

To encourage better study habits by using computer vision to detect common distractions and provide immediate feedback.

## 🔮 Future Improvements

- Animated on-screen alerts.
- Study session timer.
- Focus and distraction statistics.
- Daily productivity reports.
- Customizable warning thresholds.

---

<div align="center">

### 👨‍💻 Developed by Ahmad Momin

<a href="https://github.com/ahmadmomin7">GitHub Profile</a>

⭐ **If you like this project, consider giving it a star!**

<img src="https://capsule-render.vercel.app/api?type=waving&color=00C2FF&height=100&section=footer" alt="Animated-style footer banner" />

</div>
