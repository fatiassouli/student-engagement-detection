# Engage-Moi — Student Engagement Detection

**Deep Learning · Computer Vision · Facial Action Units · Emotion Recognition · Flask**

## Overview

Engage-Moi is an academic deep learning project that explores student engagement estimation through facial analysis. It combines computer vision and deep learning techniques to analyze facial expressions and derive indicators related to emotional states and engagement.

The application provides a web interface built with Flask and supports image-based analysis as well as webcam-based facial analysis.

## Features

- **Facial analysis:** Processes facial images using computer vision techniques.
- **Deep learning inference:** Uses a ResNet50-based model checkpoint for prediction.
- **Emotion-related analysis:** Explores facial expression patterns and emotion-related indicators.
- **Action Unit analysis:** Presents facial Action Units as part of the facial analysis workflow.
- **Image upload:** Allows users to submit an image for analysis.
- **Webcam interface:** Provides a webcam-based analysis interface for local use.
- **Web application:** Uses Flask, HTML and CSS to provide an accessible interface.

## Technologies

- **Programming language:** Python
- **Deep learning:** PyTorch, Torchvision, ResNet50
- **Computer vision:** OpenCV
- **Image processing:** Pillow, NumPy
- **Backend:** Flask
- **Frontend:** HTML, CSS

## Project Structure

```text
student-engagement-detection/
├── app2.py
├── README.md
├── requirements.txt
├── .gitignore
├── models/
│   └── resnet50.pth
├── static/
│   ├── image/
│   └── style.css
└── templates/
    ├── camera.html
    ├── detecte.html
    ├── footer.html
    ├── header.html
    ├── index.html
    └── teste.html
```

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/fatiassouli/student-engagement-detection.git
cd student-engagement-detection
```

### 2. Create a virtual environment

On Windows:

```powershell
py -3.11 -m venv .venv
.venv\Scripts\activate
```

On Linux or macOS:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Use a Python version compatible with the dependencies installed by the project.

### 3. Install dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Run the application

```bash
python app2.py
```

Open your browser at:

http://127.0.0.1:5000

The webcam feature requires camera access on the machine running the application.

## Model

The project includes a ResNet50 checkpoint stored in `models/resnet50.pth`.

The model is loaded by the application for inference. The exact training dataset, training configuration, and quantitative evaluation metrics should be documented separately when those details are available.

## Limitations and Responsible Use

Facial expressions do not provide a definitive measurement of a student's attention, understanding, motivation, or engagement.

Predictions should be interpreted as experimental indicators rather than objective assessments of a learner. The application should not be used to make high-impact educational decisions about students.

When testing the application, use images and video for which you have appropriate permission. Avoid publishing identifiable images or personal data.

## Future Improvements

- Add quantitative evaluation metrics and documented test results.
- Improve model evaluation across different lighting conditions and facial characteristics.
- Add input validation and upload size limits.
- Provide reproducible dependency versions and deployment instructions.
- Add application screenshots and a model evaluation report.

## Author

**Fatima Zahraa Assouli**

Master's student in Artificial Intelligence

GitHub: [@fatiassouli](https://github.com/fatiassouli)

---

*Academic project exploring deep learning and computer vision for student engagement estimation.*