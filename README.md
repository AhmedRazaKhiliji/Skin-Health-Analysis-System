🩺 Skin Health Analysis System (SHAS)

The Skin Health Analysis System (SHAS) is an AI-powered web application designed to detect and classify common skin diseases from user-uploaded images using deep learning (CNN).
Built with Flask, TensorFlow, and NumPy, SHAS can predict conditions such as:

🦠 Cellulitis | Impetigo | Athlete’s Foot | Nail Fungus | Ringworm | Cutaneous Larva Migrans | Chickenpox | Shingles

with up to 90% accuracy.

🚀 Features

🧠 AI-based Detection — Uses a trained CNN model to identify skin diseases

💻 Flask Web Interface — Simple and user-friendly design

📸 Multi-image Upload — Upload one or more skin images for analysis

📋 Pre-analysis Questionnaire — Collects basic user info before prediction

📄 PDF Report Generation — Exports personalized reports with details, precautions, and treatments

🎨 Modern Medical UI — Clean blue-white theme for a professional look

🧩 Tech Stack

Frontend: HTML, CSS, Bootstrap 5

Backend: Flask (Python)

Machine Learning: TensorFlow, Keras, NumPy

PDF Generation: ReportLab

⚙️ How It Works

User fills out a short questionnaire

Uploads one or more skin images

The AI model processes and classifies the disease

The system displays disease info, precautions, and treatment

User can download a detailed PDF report

📁 Project Structure
SHAS/
│
├── static/              # CSS, JS, and image assets
├── templates/           # HTML templates
├── model/               # Trained CNN model (.keras or .h5 file)
├── app.py               # Main Flask application
├── requirements.txt     # Project dependencies
└── README.md            # Project documentation

🧠 Model Details

The CNN model is trained on a labeled dataset of eight skin conditions, achieving around 90% accuracy. It uses image preprocessing and augmentation for better generalization.

🩹 Objective

SHAS aims to assist users and healthcare professionals by providing early skin disease detection through an accessible, AI-driven web platform.
