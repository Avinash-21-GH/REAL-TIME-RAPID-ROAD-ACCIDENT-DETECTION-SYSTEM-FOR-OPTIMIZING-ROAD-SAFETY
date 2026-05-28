# Real-Time Rapid Accident Detection System

## Overview

This project is an AI-based real-time accident detection system developed using YOLO object detection, OpenCV, Flask, and Python. The system continuously monitors traffic video streams, detects vehicles, analyzes their movement, and identifies possible accidents in real time.

The project is designed to improve road safety by reducing accident response time and providing intelligent monitoring using Computer Vision and Deep Learning techniques.

---

# Features

* Real-time vehicle detection using YOLO
* Vehicle tracking and motion analysis
* Accident confirmation mechanism
* Live dashboard monitoring
* Real-time video streaming
* Confidence score display
* Flask web application
* Smart traffic monitoring
* Multi-frame voting system
* Accident alert indication

---

# Technologies Used

## Backend

* Python
* Flask
* OpenCV
* NumPy
* Ultralytics YOLO

## Frontend

* HTML
* CSS
* JavaScript

---

# Project Structure

```text
AccidentDetectionProject/
│
├── app.py
├── requirements.txt
├── README.md
├── PROJECT_DEMO_SCRIPT.txt
├── sample_accident_video.mp4
│
├── templates/
│   └── index.html
│
└── static/
```

---

# Hardware Requirements

* Intel Core i5 / Ryzen 5 or higher
* Minimum 8GB RAM
* 512GB Storage
* Webcam or traffic video input
* Internet connection (optional)

---

# Software Requirements

* Windows 10 / Windows 11
* Python 3.10+
* VS Code or any IDE

---

# Installation Steps

## Step 1: Extract ZIP File

Extract:

```text
AccidentDetectionProject.zip
```

---

## Step 2: Open Project Folder

Open the folder in VS Code.

---

## Step 3: Open Terminal

Go to:

```text
Terminal → New Terminal
```

---

## Step 4: Install Dependencies

Run:

```bash
pip install -r requirements.txt
```

---

## Step 5: Add Video File

Place your traffic accident video inside the project folder and rename it:

```text
sample_accident_video.mp4
```

---

## Step 6: Run Project

Run:

```bash
python app.py
```

---

## Step 7: Open Browser

Open:

```text
http://127.0.0.1:5000
```

---

# System Workflow

1. Capture video frames
2. Preprocess video frames
3. Detect vehicles using YOLO
4. Track vehicle movement
5. Analyze motion patterns
6. Detect abnormal vehicle behavior
7. Confirm accident using multi-frame logic
8. Display results on dashboard

---

# Accident Detection Logic

The system detects accidents using:

* Sudden speed reduction
* Vehicle proximity
* Motion irregularities
* Multi-frame voting confirmation

An accident is confirmed only if multiple consecutive frames satisfy abnormal behavior conditions.

---

# Dashboard Features

* Live video feed
* Vehicle detection boxes
* Detection count
* Confidence percentage
* Accident status monitoring

---

# Output

## Normal Condition

* Dashboard displays:

  * ALL CLEAR

## Accident Detected

* Dashboard displays:

  * ACCIDENT CONFIRMED
* Confidence increases
* Red alert indication appears

---

# Future Enhancements

* SMS alert integration
* Email notification system
* GPS tracking
* Cloud storage
* Live CCTV integration
* Mobile application support

---

# Demo Video Flow (3–5 Minutes)

1. Open project folder
2. Show project structure
3. Install dependencies
4. Run app.py
5. Open browser
6. Show live detection
7. Explain dashboard
8. Demonstrate accident detection
9. Explain future scope

---

# Author

B. Avinash
B.Tech - Computer Science and Engineering
Hyderabad Institute of Technology and Management (HITAM)

---

# Conclusion

This project demonstrates the practical implementation of Artificial Intelligence and Computer Vision for intelligent transportation systems. The system successfully performs real-time accident monitoring, vehicle tracking, and accident confirmation using YOLO and motion analysis techniques.
