# AI-Based Driver Drowsiness Detection System

## Project Overview

An AI-based real-time driver drowsiness detection system developed using **Python, OpenCV, and MediaPipe**. The system monitors facial features through a webcam and detects signs of driver fatigue such as prolonged eye closure and yawning.

## Objective

The main objective is to detect early signs of driver drowsiness in real time and provide an alert to help prevent fatigue-related accidents.

## Technologies Used

* Python
* OpenCV
* MediaPipe
* NumPy
* Computer Vision
* Facial Landmark Detection
* Eye Aspect Ratio (EAR)
* Mouth Aspect Ratio (MAR)

## How It Works
Webcam
   ↓
Video Frame Capture
   ↓
MediaPipe Face Landmark Detection
   ↓
Eye & Mouth Landmark Extraction
   ↓
EAR / MAR Calculation
   ↓
Drowsiness Detection
   ↓
Alert

##  Key Features

* Real-time webcam-based monitoring
* Facial landmark detection using MediaPipe
* Eye closure detection using **Eye Aspect Ratio (EAR)**
* Yawning detection using **Mouth Aspect Ratio (MAR)**
* Real-time drowsiness identification
* Alert mechanism for detected drowsiness

##  Project Structure

Driver-Drowsiness-Detection/
│
├── Driver_Drowsiness_Detection.ipynb
├── requirements.txt
├── images/
│   ├── eye_landmarks.png
│   └── mouth_landmarks.png
└── demo/
    └── drowsiness_detection_demo.mp4


##  How to Run

### 1. Clone the repository

git clone <your-github-repository-url>

### 2. Install required libraries

pip install -r requirements.txt

### 3. Open the Jupyter Notebook

jupyter notebook

Open:

`Driver_Drowsiness_Detection.ipynb`

### 4. Run the notebook

Run the cells sequentially and allow access to your webcam when prompted.

## Results

The system successfully detects facial landmarks and identifies potential signs of drowsiness through eye closure and yawning using real-time webcam input.

## images
<img width="800" height="571" alt="eyes_mouth_landmarks" src="https://github.com/user-attachments/assets/690e0040-5e60-4589-93eb-65ec2f299e0b" />


## Demo


https://github.com/user-attachments/assets/05670131-a70c-48b6-acbc-efc2e2a6defd


## Future Enhancements

* Improve robustness under low-light conditions
* Add CNN/LSTM-based fatigue classification
* Integrate additional driver behavior signals
* Deploy the system on edge devices
* Add advanced audio and visual alert mechanisms

## Project

**AI-Based Driver Drowsiness Detection System**

**Technologies:** Python | OpenCV | MediaPipe | Computer Vision | EAR | MAR
