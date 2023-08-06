# Driver Drowsiness Detection System

## Description
This project implements a Driver Drowsiness Detection System using computer vision and machine learning techniques. The system detects the level of drowsiness of a driver in real-time using a camera feed. It can be used as a safety measure to alert drivers when they show signs of drowsiness, thereby reducing the risk of accidents caused by fatigue.

## Features
- Real-time drowsiness detection using a webcam feed.
- Alerts the driver with visual and audio cues when drowsiness is detected.
- Collects and displays statistics on drowsy events and alerts.
- User-friendly GUI for easy interaction.

### Prerequisites
- Python 
- OpenCV
- Dlib
- Scikit-learn
- Playsound
- Numpy

### Clone the repository
```bash
git clone https://github.com/Sankalp20000/DriverDrowsiness.git
cd DriverDrowsiness

Usage:
1) Make sure you have all the required dependencies installed.
2) Run the Driver_drowsiness.py script to start the application.
3) The application will access your webcam to detect your drowsiness in real-time.
4) Adjust the sensitivity settings as needed by using the on-screen controls.
5) The system will raise visual and audio alerts when drowsiness is detected.

How it works: 
The driver drowsiness detection system is based on a combination of computer vision and machine learning techniques. It follows these steps:
1) Face Detection: The system uses Haar Cascades to detect the face in the webcam feed.
2) Facial Landmark Detection: Dlib is employed to detect the facial landmarks, especially the eyes.
3) Eye Aspect Ratio (EAR) Calculation: EAR is calculated to determine the eye openness, indicating drowsiness.
4) Drowsiness Classification: A machine learning model classifies the EAR values to detect drowsiness.
5) Alerting the Driver: Visual and audio cues are generated to alert the driver when drowsiness is detected.

Contributing: 
Contributions to this project are welcome. If you find any issues or have ideas for improvements, please open an issue or create a pull request. Your feedback is valuable!

License: 
MIT License

Acknowledgments: 
The face detection and landmark detection techniques are based on the works of OpenCV and Dlib.
The EAR calculation and drowsiness classification are inspired by the research in this field.

Contact: 
For any questions or inquiries, please reach out via GitHub.
