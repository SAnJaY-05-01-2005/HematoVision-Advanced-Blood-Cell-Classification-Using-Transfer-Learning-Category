# 🔬 Hematovision: Advanced Blood Cell Classification

An intelligent web-based application for automatic blood cell classification using Transfer Learning and MobileNetV2 deep learning model.

**Project Title:** Hematovision - An Advanced Blood Cells Classification using Transfer Learning
**Team ID:** LTVIP2026TMIDS65848
**Program:** SmartBridge Long Internship

---

## 👥 Team Members

| Role            | Name                    |
| --------------- | ----------------------- |
| **Team Leader** | Annangi Harsha          |
| **Team Member** | Balireddy Raghava Priya |
| **Team Member** | Bendadi Vardhan         |
| **Team Member** | Bhukya Pavan Nayak      |

---

## 📋 Project Overview

Hematovision is a Flask-based web application that leverages transfer learning with the MobileNetV2 model to classify blood cell images into three categories:

* **RBC** (Red Blood Cells)
* **WBC** (White Blood Cells)
* **Platelet** (Platelets)

The application provides a user-friendly interface for uploading microscopic blood cell images and receiving instant classification results with confidence scores.

---

## ✨ Features

* 🎯 **Accurate Classification** — Uses pre-trained MobileNetV2 with transfer learning
* 🖼️ **Web-based Interface** — Built using Flask
* 📱 **Responsive Design** — Works on desktop & mobile
* 🎨 **Modern UI** — Medical theme (teal & emerald)
* ⚡ **Fast Processing** — Lightweight deep learning model
* 📊 **Confidence Scores** — Displays prediction probability

---

## 🛠️ Tech Stack

* **Backend:** Python 3.12, Flask
* **Deep Learning:** TensorFlow / Keras (MobileNetV2)
* **Frontend:** HTML5, CSS3, JavaScript
* **Database:** Optional
* **Deployment:** AWS / Heroku / Local Server

---

## 📦 Installation

### 🔹 Prerequisites

* Python 3.8+
* pip package manager

---

### 🔹 Setup Instructions

1️⃣ **Clone Repository**

```bash
git clone https://github.com/your-username/Hematovision.git
cd Hematovision-main/Project
```

2️⃣ **Create Virtual Environment (Optional)**

```bash
python -m venv venv
venv\Scripts\activate      # Windows
source venv/bin/activate   # Linux/Mac
```

3️⃣ **Install Dependencies**

```bash
pip install -r templates/requirements.txt
```

4️⃣ **Run Application**

```bash
python app.py
```

5️⃣ **Open Browser**

```
http://localhost:5000
```

---

## 🚀 Usage

1. Upload blood cell image
2. Click **Classify Blood Cell**
3. View prediction + confidence score

Supported formats: JPG, JPEG, PNG

---

## 📁 Project Structure

```
Hematovision-main/
├── Project/
│   ├── app.py
│   ├── create_model.py
│   ├── generate_demo_images.py
│   ├── requirements.txt
│   ├── static/
│   │   ├── style.css
│   │   └── images/
│   │       ├── demo_rbc.png
│   │       ├── demo_wbc.png
│   │       ├── demo_platelet.png
│   │       └── demo_mixed.png
│   ├── templates/
│   │   ├── blood_cell_classifier_mobilenetv2 (1).h5
│   │   ├── home.html
│   │   ├── result.html
│   │   └── requirements.txt
│   └── Dataset/
└── README.md
```

---

## 🧠 Model Details

* **Model:** CNN
* **Architecture:** MobileNetV2
* **Transfer Learning:** Yes
* **Input Size:** 224×224
* **Classes:** RBC, WBC, Platelet

---

## 📊 Testing with Demo Images

Run:

```bash
python generate_demo_images.py
```

Location:

```
static/images/
```

Files:

* demo_rbc.png
* demo_wbc.png
* demo_platelet.png
* demo_mixed.png

---

## 🎨 Color Scheme

| Color     | Code      | Usage      |
| --------- | --------- | ---------- |
| Teal      | #0891b2   | Primary    |
| Dark Teal | #0e7490   | Hover      |
| Emerald   | #10b981   | Confidence |
| Light BG  | Blue-Gray | Theme      |

---

## 🔄 Workflow

```
Upload Image
   ↓
Flask Backend
   ↓
Preprocessing (224×224)
   ↓
MobileNetV2 Inference
   ↓
Prediction Output
   ↓
Result + Confidence
```

---

## 🚀 Future Enhancements

* Add more WBC subtypes
* Batch image processing
* Data analytics dashboard
* REST API integration
* Cloud deployment
* Retraining pipeline
* Confidence alerts
* User history tracking

---

## 📝 Requirements

Main libraries:

* TensorFlow / Keras
* Flask
* OpenCV
* NumPy
* Scikit-learn

See full list in:

```
templates/requirements.txt
```

---

## ⚠️ Disclaimer

For educational & research use only.
Not approved for clinical diagnosis.

---

## 📧 Contact

Reach out to team members for queries or collaboration.

---

## 📄 License

Developed under SmartBridge Long Internship Program 2025.

---

**Last Updated:** February 17, 2026
**Status:** Active Development ✅
