# Driver Drowsiness and Yawning Detection System

A real-time computer vision application that monitors driver alertness using a webcam, MediaPipe Face Mesh, and OpenCV.

## Features

- Real-time face landmark detection
- Eye Aspect Ratio (EAR) for detecting closed eyes
- Mouth Aspect Ratio (MAR) for detecting yawning
- Live drowsiness status and detection counters
- Tkinter graphical user interface
- Start and stop live detection controls

## Technologies

- Python
- OpenCV
- MediaPipe Face Mesh
- NumPy
- Tkinter
- Pillow

## Installation

1. Install Python 3.11.
2. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/driver-drowsiness-detection.git
   cd driver-drowsiness-detection
   ```

3. Create and activate a virtual environment:

   **Windows PowerShell**

   ```powershell
   py -3.11 -m venv venv
   .\venv\Scripts\Activate.ps1
   ```

4. Install dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

## Run the Application

```bash
python driver_drowsiness_detection.py
```

Allow camera access if Windows requests permission.

## Requirements

- Windows or another compatible desktop operating system
- A working webcam
- Python 3.11
- Internet access for initial dependency installation

## Disclaimer

This project is intended for educational and demonstration purposes. It is not a certified driver-safety system and should not be relied upon as the sole means of preventing accidents.

## License

Choose an appropriate open-source license before distributing this project.
