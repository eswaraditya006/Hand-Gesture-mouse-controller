# 👋 Hand Gesture Mouse Controller

Control your computer with just your fingers — no mouse needed!

This project turns your webcam into a **virtual mouse controller** using simple hand gestures. Move your hand, and watch your cursor follow. Pinch your fingers, and *click* — it’s that easy.

Built with 💡 **Python**, 🎯 **MediaPipe**, and 🖼 **OpenCV**.

---

## 🎥 What It Can Do

✅ Move your mouse with your **index finger**  
✅ Click by pinching your **index and middle fingers**  
✅ Works on any screen size  
✅ Super smooth motion with real-time tracking

---

## 🚀 Getting Started

### 1. Install the Requirements


pip install opencv-python mediapipe pyautogui numpy




###2. Run the App

python main.py


Allow camera permissions if prompted. That’s it!



🖐 How to Use It
✋ Raise one hand in front of your webcam.

👉 Raise just your index finger → move the mouse.

✌️ Raise index + middle finger → pinch to click.

Stay inside the purple box on screen for best results.

###🧠 How It Works (Simplified)
MediaPipe tracks 21 landmarks on your hand.

It watches your index finger (tip id 8) to control the mouse.

If index and middle fingers (tip ids 8 & 12) come close, it triggers a click.

PyAutoGUI translates those hand movements into actual mouse actions on your screen.

###🧰 Tech Stack
Python

OpenCV

MediaPipe

PyAutoGUI

NumPy

###📸 Sneak Peek
Add a screenshot or GIF here to showcase how it works in real time.

###💡 Future Ideas
Drag & drop with thumb + index.

Gesture-based scrolling (e.g., swipe up/down).

Control volume, brightness, or even slideshows.
