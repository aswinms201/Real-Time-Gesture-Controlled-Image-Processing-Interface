# Real-Time Gesture-Controlled Image Editor

A touchless virtual photo editing application built with Python. This project utilizes computer vision to track hand gestures in real-time, allowing users to apply image processing filters using a spatial "Minority Report" style interface.

## 🚀 Features
* **Bimanual UI Tracking:** Differentiates between left and right hands for distinct user interface interactions.
* **Left-Hand Menu:** Select active editing tools by hovering your left index finger over virtual buttons.
* **Right-Hand Control:** Adjust the intensity of the selected tool (0-100) using a horizontal slider mapped to your right index finger.
* **Available Filters:** Adjust Exposure, Contrast, Sharpness, Saturation, Temperature, and Vignette. 
* **Touchless Saving:** Includes a spatial "SAVE" button in the top right corner with a 2-second cooldown to prevent accidental overwrites.
* **Dual Display Output:** Shows the live webcam interaction stream (1920x1080) alongside an active preview window (800x550) for the edited image.

## 🛠️ Tech Stack
* **Python**
* **OpenCV** (Real-time image manipulation, rendering, GUI)
* **MediaPipe** (Hand landmark tracking and classification)
* **NumPy** (Matrix operations and array interpolations)

## ⚙️ Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YourUsername/Your-Repository-Name.git](https://github.com/YourUsername/Your-Repository-Name.git)
   cd Your-Repository-Name
