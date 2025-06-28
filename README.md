# 🌿 Praakuthi

A web-based machine learning application for detecting plant diseases through image classification. Built with Python, Flask, and a deep learning model trained on plant leaf imagery.

---

## 📚 Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Model Details](#model-details)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [Troubleshooting](#troubleshooting)
- [Contributors](#contributors)
- [License](#license)

---

## 🌱 Introduction

**Praakuthi** leverages deep learning to identify plant diseases from uploaded leaf images. It provides a clean user interface where users can drag and drop images to receive a diagnosis. This helps farmers and agricultural researchers detect and manage plant health more effectively.

---

## ✨ Features

- 🌿 Upload leaf images to detect diseases
- 🔍 Predicts using a pre-trained Keras CNN model
- ⚡ Fast, lightweight Flask backend
- 💡 Clean UI with drag-and-drop support
- 🚀 Deployable via [Vercel](https://vercel.com/)

---

## 🚀 Demo

> *You can add a hosted demo link here once deployed.*

Example usage:
- Upload a leaf image
- Get a prediction like: `Tomato___Bacterial_spot`

---

## 🛠️ Installation

### Prerequisites

- Python 3.7+
- `pip` or `conda` for managing packages

### Steps

```bash
# Clone the repository
git clone https://github.com/bala-rajesh/Praakuthi.git
cd Praakuthi

# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
You said:
https://github.com/bala-rajesh/Praakuthi


ChatGPT said:
I found the GitHub repository you linked, bala-rajesh/Praakuthi. Here's a breakdown of what it includes:

📁 Repository Overview
Primary tech: Python (Jupyter Notebook, Flask app), HTML, CSS for the UI 
github.com
+4
github.com
+4
github.com
+4

Main files:

app.py, model.py, utils.py – core Flask app and ML model logic

Train_plant_disease.ipynb – notebook used to train a plant disease classification model

trained_plant_disease_model.keras – pre-trained model file

static/ and templates/ – frontend assets

requirements.txt – Python dependencies list

Deployment: Configured for Vercel hosting (vercel.json) 
github.com
+2
github.com
+2
github.com
+2

License: Apache‑2.0 
github.com

✅ Project Purpose
Based on the contents, this appears to be an early-stage project aimed at identifying plant diseases via image uploads. The user interacts with a Flask frontend, uploads an image, and the app predicts and displays potential plant diseases using a machine learning model trained in the included notebook.

📝 README Status
The repo currently lacks a proper README outlining:

What the project does

Installation steps

How to run locally

Screenshots or demo link

Description of the model architecture

Contribution guidelines

Would you like me to generate a full README in Markdown—including sections like Installation, Usage, Features, and so on? If you could share any additional details (e.g., demo page, CLI commands, example outputs), I can make it even more thorough.








Sources
You said:
Yes


ChatGPT said:
Great! Below is a comprehensive README.md for the Praakuthi project, based on the repository contents and typical best practices. You can copy this into your repo and edit any details you'd like to adjust or expand.

markdown
Copy
Edit
# 🌿 Praakuthi

A web-based machine learning application for detecting plant diseases through image classification. Built with Python, Flask, and a deep learning model trained on plant leaf imagery.

---

## 📚 Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Model Details](#model-details)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [Troubleshooting](#troubleshooting)
- [Contributors](#contributors)
- [License](#license)

---

## 🌱 Introduction

**Praakuthi** leverages deep learning to identify plant diseases from uploaded leaf images. It provides a clean user interface where users can drag and drop images to receive a diagnosis. This helps farmers and agricultural researchers detect and manage plant health more effectively.

---

## ✨ Features

- 🌿 Upload leaf images to detect diseases
- 🔍 Predicts using a pre-trained Keras CNN model
- ⚡ Fast, lightweight Flask backend
- 💡 Clean UI with drag-and-drop support
- 🚀 Deployable via [Vercel](https://vercel.com/)

---

## 🚀 Demo

> *You can add a hosted demo link here once deployed.*

Example usage:
- Upload a leaf image
- Get a prediction like: `Tomato___Bacterial_spot`

---

## 🛠️ Installation

### Prerequisites

- Python 3.7+
- `pip` or `conda` for managing packages

### Steps

```bash
# Clone the repository
git clone https://github.com/bala-rajesh/Praakuthi.git
cd Praakuthi

# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
▶️ Usage
Start the Flask app locally:

bash
Copy
Edit
python app.py
Then open your browser and navigate to:

arduino
Copy
Edit
http://localhost:5000
Upload an image and view the prediction results.

🧠 Model Details
The model is a Convolutional Neural Network (CNN) trained using TensorFlow/Keras.

Training is performed via Train_plant_disease.ipynb.

Final model is saved as trained_plant_disease_model.keras.

You can retrain or fine-tune the model using your own dataset by modifying the notebook.

📁 Project Structure
php
Copy
Edit
Praakuthi/
├── app.py                  # Flask web app
├── model.py                # Model loading and prediction
├── utils.py                # Helper functions
├── templates/              # HTML templates
├── static/                 # CSS and images
├── Train_plant_disease.ipynb  # Training notebook
├── trained_plant_disease_model.keras  # Pretrained model
├── requirements.txt
└── vercel.json             # Vercel deployment config
📦 Dependencies
Install with:

bash
Copy
Edit
pip install -r requirements.txt
Key packages include:

Flask

TensorFlow / Keras

NumPy

OpenCV (cv2)

Pillow

⚙️ Configuration
Modify model.py if you're changing the model architecture or file path.

You can update frontend assets in the static/ and templates/ folders.

For Vercel deployment, edit vercel.json as needed.

🧩 Troubleshooting
App not loading: Make sure you're running with the correct Python environment and all packages are installed.

Model file missing: Ensure trained_plant_disease_model.keras is in the root directory or update the model path in model.py.

File upload errors: Ensure images are in supported formats (JPEG/PNG).

👥 Contributors
Bala Rajesh — Creator & Developer

Feel free to open a pull request if you'd like to contribute!

📄 License
This project is licensed under the Apache 2.0 License.
