# AI Border Surveillance Command Center

An AI-powered intelligent border surveillance and acoustic threat detection system using Audio Spectrogram Transformers (AST), real-time monitoring dashboards, and threat evaluation visualization.

---

# 📌 Project Overview

This project detects and classifies potential border threats using environmental audio analysis and deep learning. The system uses transformer-based audio classification to identify suspicious acoustic activities such as:

- Human Intrusion
- Drone Threat
- Animal Threat
- Environmental Noise

The platform provides:

- Real-time surveillance dashboard
- AI threat confidence monitoring
- Tactical radar visualization
- Threat analytics
- Evaluation console
- Multi-fold audio classification pipeline

---

# 🚀 Features

## 🔥 AI Threat Detection
- Transformer-based AST model
- Real-time audio classification
- Confidence-calibrated predictions
- Multi-class threat detection

## 📊 Surveillance Dashboard
- Live monitoring interface
- Tactical radar simulation
- Threat confidence gauge
- Threat level visualization
- Real-time alerts

## 📈 Evaluation Console
- Live accuracy monitoring
- Class-wise evaluation
- Prediction logging
- Progress visualization
- High-confidence evaluation metrics

## ⚡ Optimized ML Pipeline
- Multi-fold dataset training
- Balanced preprocessing
- Early stopping
- Confidence filtering
- Dynamic class weighting

---

# 🧠 Model Architecture

The system uses a pretrained Audio Spectrogram Transformer (AST) for intelligent acoustic threat classification.

## Workflow

Audio Input
     ↓
feature_extractor.py
     ↓
Mel Spectrogram Extraction
     ↓
Feature Normalization
     ↓
Audio Spectrogram Transformer (AST)
     ↓
Threat Classification
     ↓
Confidence Calibration
     ↓
Dashboard Visualization

📂 Threat Classes

Class ID	Threat Type

0	Human Intrusion
1	Drone Threat
2	Animal Threat
3	Environmental Noise

⚙️ System Workflow

1️⃣ Audio Collection

Environmental audio is collected from the UrbanSound8K dataset and processed for threat simulation.

2️⃣ Feature Extraction

The feature_extractor.py module handles:

Audio preprocessing
Resampling
Mel Spectrogram generation
Feature normalization
AST-compatible formatting

3️⃣ Dataset Preprocessing

The precompute_features.py module performs:

Multi-fold dataset loading
Balanced dataset creation
Feature caching
Training/test split preparation

4️⃣ Model Training

The AST model is fine-tuned using:

Balanced training
Multi-fold learning
Weighted loss optimization
Early stopping
Transformer fine-tuning

5️⃣ Threat Prediction

The trained transformer model predicts:

Threat category
Confidence score
Threat probability distribution

6️⃣ Monitoring Dashboard

Predictions are visualized through:

Threat radar
Confidence indicators
Tactical monitoring interface
Real-time analytics

7️⃣ Evaluation Console

The system evaluates:

Accuracy
Coverage
Class-wise performance
High-confidence predictions


🏗️ Project Structure
Border_Surveillance_Project/
│
├── core/
│   ├── feature_extractor.py
│   ├── precompute_features.py
│   ├── predictor.py
│   ├── train_model.py
│
├── models/
│   ├── ast_model.py
│
├── ui/
│   ├── dashboard.py
│   ├── evaluation_ui.py
│
├── data/
│
├── dataset.py
├── config.py
├── evaluate_model.py
├── main.py
│
└── README.md


🧪 Dataset

Dataset Used
UrbanSound8K

Training Strategy

Multi-fold balanced training
Fold-based evaluation
Environmental audio mapping
Confidence-based prediction filtering

📊 Performance

Metric	Result
Full Accuracy	~74%
High Confidence Accuracy	~78%
Coverage	~95%

🛠️ Technologies Used

Python
PyTorch
Torchaudio
HuggingFace Transformers
Tkinter
NumPy
Scikit-learn
TQDM

▶️ Installation

Clone Repository
git clone https://github.com/Henil994/Environmental-Noise-vs-Threat-Detection-System-for-Border-Surveillance-using-Machine-Learning.git

Install Dependencies

pip install torch torchaudio transformers scikit-learn tqdm numpy

🚀 Run Project

1️⃣ Precompute Features
python -m core.precompute_features

2️⃣ Train Model
python -m core.train_model

3️⃣ Evaluate Model
python evaluate_model.py

4️⃣ Launch Surveillance Dashboard
python main.py

📈 Evaluation Metrics

The project measures:

Overall Accuracy
High-Confidence Accuracy
Coverage Percentage
Precision
Recall
F1-Score

🔐 Future Improvements

Live microphone integration
Real border sensor deployment
Thermal camera fusion
Drone sound localization
Edge AI optimization
Real-time streaming support

👨‍💻 Author
Henil Patel

AI-based Border Surveillance and Threat Detection System using Audio Spectrogram Transformers and Machine Learning.

📌 Disclaimer

This project is developed for academic and research purposes to simulate AI-assisted border surveillance using environmental audio analysis.
