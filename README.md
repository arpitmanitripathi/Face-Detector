# 🤖 Face Detector App

An Android application that detects human faces in real-time using **Google's ML Kit**. It identifies facial features such as eyes, smile, and head rotation, and overlays detection boxes on the camera preview.

## 🧠 Features

- Real-time face detection using **ML Kit**
- Detects:
  - Facial landmarks (eyes, nose, mouth)
  - Head rotation (Euler angles)
  - Expressions (smiling, eyes open)
- Live camera preview with bounding boxes
- Fast and optimized for mobile devices

## 🔍 How It Works

- Frames are processed by **ML Kit’s Face Detection API**
- Detected faces are drawn on screen with overlays
- Information (like smiling probability) is extracted and displayed

## 🚀 Tech Stack

- **Language:** Kotlin  
- **IDE:** Android Studio  
- **ML:** Google ML Kit (Face Detection)  
- **UI:** XML Layouts
