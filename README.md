# 🚨 AI Border Surveillance Command Center

AI-powered border surveillance and acoustic threat detection system using Audio Spectrogram Transformers (AST), real-time monitoring dashboards, and intelligent threat evaluation.

---

# 📌 Overview

This project classifies environmental audio into border-related threat categories using deep learning and transformer-based audio analysis.

### 🎯 Threat Categories
- Human Intrusion
- Drone Threat
- Animal Threat
- Environmental Noise

The system provides:
- Real-time monitoring dashboard
- Threat confidence analysis
- Tactical radar visualization
- Evaluation console
- Multi-fold audio classification pipeline

---

# 🚀 Features

## 🔥 AI Threat Detection
- AST-based transformer model
- Real-time audio prediction
- Confidence-calibrated outputs
- Multi-class threat classification

## 📊 Surveillance Dashboard
- Live monitoring UI
- Threat confidence meter
- Tactical radar simulation
- Threat analytics visualization

## 📈 Evaluation Console
- Live accuracy monitoring
- Class-wise evaluation
- Prediction logs
- High-confidence metrics

## ⚡ Optimized Training Pipeline
- Balanced dataset generation
- Multi-fold training
- Early stopping
- Dynamic class weighting
- Transformer fine-tuning

---

# 🧠 Model Architecture

```
Audio Input
    ↓
feature_extractor.py
    ↓
Mel Spectrogram
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
```

---

# 📂 Threat Classes

| ID | Threat Type |
|----|-------------|
| 0 | Human Intrusion |
| 1 | Drone Threat |
| 2 | Animal Threat |
| 3 | Environmental Noise |

---

# ⚙️ System Workflow

## 1️⃣ Audio Collection
Environmental audio samples are collected using the UrbanSound8K dataset.

## 2️⃣ Feature Extraction
`feature_extractor.py` performs:
- Audio preprocessing
- Resampling
- Mel Spectrogram generation
- Feature normalization

## 3️⃣ Dataset Preprocessing
`precompute_features.py` handles:
- Balanced dataset generation
- Multi-fold loading
- Feature caching
- Train-test split preparation

## 4️⃣ Model Training
The AST model is trained using:
- Weighted loss optimization
- Early stopping
- Transformer fine-tuning
- Multi-fold training strategy

## 5️⃣ Threat Prediction
The trained model predicts:
- Threat category
- Confidence score
- Threat probability distribution

## 6️⃣ Dashboard Monitoring
Predictions are visualized using:
- Tactical radar
- Confidence indicators
- Threat analytics
- Live monitoring UI

## 7️⃣ Evaluation
The evaluation console measures:
- Accuracy
- Coverage
- Precision
- Recall
- F1-score

---

# 🏗️ Project Structure

```
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
├── dataset.py
├── config.py
├── evaluate_model.py
├── main.py
│
└── README.md
```

---

# 🧪 Dataset

### Dataset Used
- UrbanSound8K

### Training Strategy
- Multi-fold balanced training
- Fold-based evaluation
- Confidence-based filtering

---

# 📊 Performance

| Metric | Result |
|--------|---------|
| Full Accuracy | ~74% |
| High Confidence Accuracy | ~78% |
| Coverage | ~95% |

---

# 🛠️ Technologies Used

- Python
- PyTorch
- Torchaudio
- HuggingFace Transformers
- Tkinter
- NumPy
- Scikit-learn

---

# ▶️ Installation

## Clone Repository

```
git clone https://github.com/Henil994/Environmental-Noise-vs-Threat-Detection-System-for-Border-Surveillance-using-Machine-Learning.git
```

## Install Dependencies

```
pip install torch torchaudio transformers scikit-learn tqdm numpy
```

---

# 🚀 Run Project

## Precompute Features

```
python -m core.precompute_features
```

## Train Model

```
python -m core.train_model
```

## Evaluate Model

```
python evaluate_model.py
```

## Launch Dashboard

```
python main.py
```

---

# 🔐 Future Improvements

- Live microphone integration
- Real border sensor deployment
- Drone sound localization
- Thermal camera fusion
- Edge AI optimization

---

# 👨‍💻 Author

### Henil Patel

AI-based Border Surveillance and Threat Detection System using Machine Learning and Audio Spectrogram Transformers.

---

# 📌 Disclaimer

This project is developed for academic and research purposes to simulate AI-assisted border surveillance using environmental audio analysis.
