# VisionIQ

## AI-Powered Bone Fracture Detection and Localization System

VisionIQ is a deep learning-powered web application designed to assist in the detection and localization of bone fractures from X-ray images. The system combines image classification and object detection techniques with a Django-based web platform to provide automated fracture analysis through an intuitive and user-friendly interface.

---

## Project Overview

VisionIQ demonstrates the integration of Artificial Intelligence with web technologies to support medical image analysis. The application enables users to upload X-ray images, automatically classify them as **Fractured** or **Normal**, and localize fracture regions when detected.

The project combines **ResNet50** for fracture classification and **YOLOv8** for fracture localization, providing an end-to-end workflow for AI-assisted fracture analysis.

---

## Key Features

- AI-assisted bone fracture detection from X-ray images
- Fracture localization using YOLOv8 object detection
- Secure user authentication and profile management
- Image upload with real-time prediction
- Prediction history for registered users
- Administrative dashboard for user and prediction management
- Responsive and intuitive web interface

---

## System Workflow

```text
                     X-Ray Image
                          │
                          ▼
                Image Preprocessing
                          │
                          ▼
           ResNet50 Classification Model
                          │
              ┌───────────┴───────────┐
              │                       │
          Normal                 Fractured
                                      │
                                      ▼
                YOLOv8 Localization Model
                                      │
                                      ▼
                Fracture Region Detection
                                      │
                                      ▼
                 Prediction Visualization
```

---

## Technology Stack

### Backend

- Python
- Django

### Frontend

- HTML5
- CSS3
- JavaScript

### Deep Learning

- TensorFlow
- Keras
- ResNet50
- YOLOv8

### Database

- SQLite

### Development Tools

- Git
- GitHub
- Visual Studio Code

---

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/laxmi887/VisionIQ.git
cd VisionIQ
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Apply Database Migrations

```bash
python manage.py migrate
```

### 6. Run the Development Server

```bash
python manage.py runserver
```

---

## AI Models

| Model | Purpose |
|--------|---------|
| **ResNet50** | Classifies X-ray images as **Fractured** or **Normal** |
| **YOLOv8** | Detects and localizes fracture regions using bounding boxes |

---

## Future Enhancements

- Improve model accuracy using larger and more diverse datasets
- Support multi-class fracture detection
- Deploy the application using Docker and cloud infrastructure
- Generate downloadable diagnostic reports
- Enhance the user interface and overall user experience

---

## Screenshots

### Home Page

<img width="923" height="600" alt="Home Page" src="https://github.com/user-attachments/assets/d8b9746d-cfb0-49d3-9f08-a2ce77121025" />

<img width="921" height="529" alt="Home Page" src="https://github.com/user-attachments/assets/6f0e06bc-eef8-4c80-aa25-e825da8e70ce" />

---

### Image Upload Page

<img width="929" height="573" alt="Upload Page" src="https://github.com/user-attachments/assets/95fbe7cf-9323-414a-9489-e620bb2accdc" />

---

### Prediction Result

<img width="936" height="668" alt="Prediction Result" src="https://github.com/user-attachments/assets/724c8776-1b3a-4154-ba5f-3e10679dbcf5" />

---

### User Dashboard

<img width="923" height="518" alt="Dashboard" src="https://github.com/user-attachments/assets/babd7819-862d-4730-b252-06f3272f01a3" />

---

### Prediction History

<img width="923" height="518" alt="History" src="https://github.com/user-attachments/assets/18335b2e-89a0-47de-97eb-c6b4f7e2f8a9" />

---

## Author

**Laxmi Raut**

Bachelor of Science in Computer Science and Information Technology (BSc CSIT)

- GitHub: **https://github.com/laxmi887**

---

## Disclaimer

This project was developed for **academic and research purposes**. It is intended as a decision-support tool and should **not** be used as a substitute for professional medical diagnosis.
