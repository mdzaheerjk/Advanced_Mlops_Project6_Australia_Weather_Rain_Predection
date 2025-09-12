# 🌦️ Australia Weather Rain Prediction – Advanced MLOps Project

![MLOps](https://img.shields.io/badge/MLOps-Kubernetes-blue)
![Python](https://img.shields.io/badge/Python-3.10%2B-brightgreen)
![License](https://img.shields.io/badge/License-GPL--3.0-orange)
![Docker](https://img.shields.io/badge/Docker-Ready-blue)

End-to-end MLOps project for predicting rain in Australia using machine learning. This repository features a complete pipeline for data processing, model training, containerization, Kubernetes deployment, and a web application for real-time weather inference. The project is built for robustness, reproducibility, and scalable production deployment.

> 📁 **Repository:** `Advanced_Mlops_Project6_Australia_Weather_Rain_Predection`

---
<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRIIyLxZFkxV7ifyP68FBofJ4dn-QR9xgEPNQ&s" width="800" height="533">
</p>


## 🚀 Project Highlights

- ☔ **Rain Prediction:** Predicts the likelihood of rain based on Australian weather data
- 🏗️ **Modular MLOps Workflow:** Clean separation of data, code, pipeline, and deployment
- 🐳 **Dockerized:** Easily build and deploy as a container
- ☸️ **Kubernetes-Ready:** Out-of-the-box deployment with a provided manifest
- 🌐 **Web App:** User-friendly interface for live weather/rain prediction

---

## 🧠 Technical Stack

### 🛠️ Core Technologies
![Python](https://img.shields.io/badge/Python-3.10%2B-brightgreen)
![Docker](https://img.shields.io/badge/Docker-Ready-blue)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Deploy-blue)
![Flask](https://img.shields.io/badge/Flask-WebApp-lightgrey)

### 📦 Libraries & Utilities
- Pandas, NumPy, Scikit-learn (ML/data)
- Matplotlib/Seaborn (EDA)
- Flask (web app)
- YAML (config management)
- HTML/CSS (UI)

---

## 🏗️ Project Structure

```bash
Advanced_Mlops_Project6_Australia_Weather_Rain_Predection/
├── DATA/
│   └── data.csv                     # Australian weather dataset
├── CODE/
│   ├── notebook/
│   │   └── notebook.ipynb           # EDA & prototyping
│   ├── pipeline/
│   │   ├── __init__.py
│   │   └── training_pipeline.py     # ML pipeline orchestration
│   ├── src/
│   │   ├── __init__.py
│   │   ├── custom_exception.py
│   │   ├── data_processing.py
│   │   ├── logger.py
│   │   └── model_training.py
│   ├── static/
│   │   └── style.css                # Web app styling
│   ├── templates/
│   │   └── index.html               # Web app template
│   ├── Dockerfile                   # Docker build file
│   ├── application.py               # Flask app entry point
│   ├── kubernetes-deployment.yaml   # Kubernetes deployment manifest
│   ├── requirements.txt             # Python dependencies
│   ├── setup.py                     # Package info
│   ├── LICENSE
│   ├── PDF and NOTES.pdf            # Documentation/workflow
│   └── README.md
├── SETUP INSTRUCTIONS               # Deployment guidance
├── .gitignore
```

---

## ⚡ Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/mdzaheerjk/Advanced_Mlops_Project6_Australia_Weather_Rain_Predection.git
cd Advanced_Mlops_Project6_Australia_Weather_Rain_Predection/CODE
```

### 2. Set up a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the ML pipeline
```bash
python pipeline/training_pipeline.py
```

### 5. Launch the web app
```bash
python application.py
```
Visit [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.

---

## 🐳 Docker & Kubernetes Deployment

- **Docker:**  
  Build and run the project in a container using the provided `Dockerfile`.

- **Kubernetes:**  
  Deploy on a Kubernetes cluster using `kubernetes-deployment.yaml`.

- **Setup Guidance:**  
  See `SETUP INSTRUCTIONS` and `PDF and NOTES.pdf` for step-by-step deployment and configuration help.

---

## 📊 Example Use Cases

- **Rain Forecasting:** Predicts whether it will rain tomorrow at a given location
- **Web App Demo:** Enter weather features to get instant predictions
- **MLOps Showcase:** Demonstrates automation, CI/CD, and scalable cloud deployment

---

## ✍️ Author

**Mohammed Zaheeruddin**  
🎓 First-Year B.Tech Student | AI/ML & GenAI Enthusiast  
🏫 Shetty Institute of Technology, Gulbarga  
📧 info.zaheerjk@gmail.com

---

## 📜 License

This project is licensed under the **GPL-3.0 License** – see the LICENSE file for details.

---

#### Key Features:
1. End-to-end rain prediction pipeline with modular codebase
2. Scalable, production-ready Docker and Kubernetes deployment
3. User-friendly web interface for real-time predictions
4. Designed for education, research, and real-world adaptation
