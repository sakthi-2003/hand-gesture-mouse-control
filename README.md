# 🖐️ Hand Gesture Mouse Control

### Real-Time Computer Vision System using MediaPipe + OpenCV

Control your computer mouse using just your hand — no additional hardware required.
This project leverages **MediaPipe**, **OpenCV**, and **PyAutoGUI** to enable intuitive, real-time human-computer interaction.

---

## 🚀 Features

* 🎯 Smooth and stable cursor movement
* 🤏 Click using pinch gesture (thumb + index finger)
* 📜 Scroll using finger gestures
* ⚡ Real-time performance with low latency
* 🧠 ML-powered hand landmark detection (MediaPipe)
* 🧼 Cursor smoothing to reduce jitter

---

## 🛠️ Tech Stack

* Python
* OpenCV
* MediaPipe
* PyAutoGUI

---

## 📂 Project Structure

hand-gesture-mouse-control/
│── main.py
│── requirements.txt
│── README.md

---

## ▶️ Installation & Usage

```bash
git clone https://github.com/sakthi-2003/hand-gesture-mouse-control.git
cd hand-gesture-mouse-control

pip install -r requirements.txt
python main.py
```

---

## 🎮 Gesture Controls

| Gesture                  | Action      |
| ------------------------ | ----------- |
| ☝️ Index Finger          | Move Cursor |
| 🤏 Thumb + Index (Pinch) | Left Click  |
| ✌️ Two Fingers           | Scroll      |

---

## 🧠 How It Works

* MediaPipe detects **21 hand landmarks** in real time
* Index finger tip controls cursor movement
* Distance between thumb and index finger detects click
* Finger positions control scrolling
* Smoothing reduces jitter for stability

---

## 📸 Demo

👉 Add a demo GIF here (record using OBS + upload)

---

## 🌟 Future Improvements

* Drag & Drop gesture
* Gesture-based mode switching
* GUI overlay
* Deep learning gesture classification

---

## 🤝 Contributing

Pull requests are welcome!

---

## ⭐ Project Value

This project demonstrates:

* Real-time Computer Vision
* ML-based hand tracking
* Human-computer interaction
* System optimization

---

## 🔥 Author

Sakthi

⭐ If you like this project, give it a star!
