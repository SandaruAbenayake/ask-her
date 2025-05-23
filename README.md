# ask-her
This project uses Python and machine learning to recognize hand gestures from the LeapGestRecog dataset. It can also detect gestures in real-time using your webcam.


# 🤖 Hand Gesture Message Recognizer

This project uses your webcam to detect specific hand gestures and display custom messages in real-time. It's powered by **OpenCV** and **MediaPipe**.

## ✨ Features

- Detects hand gestures in real-time using webcam
- Displays custom messages when:
  - 🤘🏻 is shown — shows a friendly message
  - 🫰🏻 is shown — shows a heartfelt message
- Works smoothly with flipped webcam feed for natural feel

## 📦 Technologies Used

- Python
- OpenCV
- MediaPipe
- Jupyter Notebook (optional for prototyping)

## 💡 How It Works

The webcam captures your hand gestures. When you show:
- 🤘🏻 → Displays: "Hi Viduni! How are you? I have something to tell you."
- 🫰🏻 → Displays: "Something special I feel about you."

## 🛠️ How to Run

1. Clone the repo
2. Install dependencies:
   ```bash
   pip install opencv-python mediapipe

