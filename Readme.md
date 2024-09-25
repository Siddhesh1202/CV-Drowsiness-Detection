# Drowsiness Detection System

This project is a prototype of a Drowsiness Detection System designed to detect signs of driver drowsiness using real-time video input and computer vision techniques. The system monitors the driver’s facial landmarks to detect eye closure and yawning, alerting the driver with a warning sound when signs of drowsiness are detected. The system also includes a performance evaluation using an ROC curve.

## Features

- **Real-time Drowsiness Detection**: Tracks eye closure and yawning to identify drowsiness.
- **Facial Landmark Detection**: Uses **dlib** to detect and track facial landmarks for eye and mouth movement monitoring.
- **Alert Mechanism**: Plays an alert sound through **VLC** when signs of drowsiness are detected.
- **ROC Curve Analysis**: Provides an evaluation metric to assess the model's accuracy using Receiver Operating Characteristic (ROC) curve analysis.

## Requirements-
    webbrowser==0.5.1
    opencv-python==4.5.3
    dlib==19.22.0
    imutils==0.5.4
    python-vlc==3.0.11115
    scipy==1.7.1


## For running the drowsiness prototype run following command:
    python3 drowsiness_detection.py


## For ROC curve run the following command 
    python3 roc_curve.py
