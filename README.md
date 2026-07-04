# ANPR and ATCC for Smart Traffic Management

An AI-powered Smart Traffic Management System that performs:
- Automatic Number Plate Recognition (ANPR)
- Automatic Traffic Counter and Classifier (ATCC)
- Vehicle Detection
- Accident Detection
- Traffic Analytics

This project is developed using Python, YOLOv8, OpenCV and OCR to automate traffic monitoring.

The system can:
- Detect vehicles
- Recognize number plates
- Detect accidents
- Count vehicles
- Detect helmet violations
- Detect triple riding
- Generate traffic analytics

# Tech Stack:
- Python
- YOLOv8
- OpenCV
- Flask
- EasyOCR
- HTML
- CSS
- JavaScript

# Folder Structure:
ANPR-System/
├── YOLO/
├── accident_detections/
├── static/
├── templates/
├── utils/
├── app.py
├── requirements.txt
├── README.md
└── LICENSE

# Installation:
* Clone the repository
* Move to project folder
- cd ANPR-and-ATCC-for-Smart-Traffic-Management
* Install dependencies
- pip install -r requirements.txt
 Run;
python app.py

# Dataset:
- Vehicle Dataset
- Number Plate Dataset
- Custom Trained YOLO Dataset

# Challenges Faced:
- Low-light vehicle detection
- Blurred number plates
- Multiple vehicles in a frame
- Real-time processing speed


# Future Improvements:
- Cloud Deployment
- Mobile App
- Multi-camera support
- Automatic Traffic Violation Detection
- Speed Detection
- Emergency Vehicle Priority


Install Tesseract OCR separately.
