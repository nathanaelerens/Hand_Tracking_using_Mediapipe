# Hand_Tracking_using_Mediapipe
### A very simple hand tracking program using Mediapipe and OpenCV.
## 🌟 Features
* **Real-time Detection:** High-speed tracking optimized for Python 3.11.
* **Landmark Mapping:** Visualizes 21 coordinates per hand (knuckles, fingertips, wrist).
* **FPS Counter:** Real-time performance monitoring displayed on the video feed.
* **Conda Optimized:** Pre-configured for environment stability on Windows.

## 🛠️ Technical Stack
* **Language:** Python 3.11.0
* **Framework:** MediaPipe (0.10.14)
* **Graphics:** OpenCV
* **Math:** NumPy (1.26.4)

## 🚀 Getting Started

### 1. Prerequisites
Ensure you have [Anaconda](https://www.anaconda.com/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) installed.

### 2. Environment Setup
Open your **Conda Prompt** and run the following:

```bash
# Create the environment
conda create -n HandTrackingMedPipe python=3.11.0 -y

# Activate the environment
conda activate HandTrackingMedPipe

# Install dependencies
pip install -r requirements.txt
