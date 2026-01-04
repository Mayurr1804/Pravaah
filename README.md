# Pravaah – Microplastic Detection System

🚀 Team Project | Competition Submission

This project was developed by a team of 3 members as part of a competition focused on microplastic detection using Machine Learning and data-driven pipelines.

🔗 Original Repository: https://github.com/Aadrika2106/Pravaah

## My Contributions
- Designed and implemented ML pipeline components
- Performed data preprocessing and feature preparation
- Trained and evaluated machine learning models

## Microplastic Detection & Water Quality Prediction System

An AI-powered system for detecting microplastics, predicting water quality, and simulating environmental impacts using machine learning, deep learning, and physics-informed models.


## Overview

This project provides an end-to-end intelligent framework to:

* Detect and classify microplastics from images
* Identify polymer types using spectroscopic ML models
* Predict and forecast Water Quality Index (WQI)
* Simulate environmental impact using a digital twin
* Support decision-making for researchers and policymakers

The system is deployed as an interactive Streamlit dashboard with role-based access.

## Key Features

### Core Models

* **YOLOv8**
  Microplastic detection and classification (Fragments, Fibers, Pellets)

* **Raman Spectroscopy ML**
  Polymer identification (PET, PE, PP, PS, PVC)

* **Random Forest**
  Water Quality Index prediction with 94% test accuracy

* **Prophet**
  60-day WQI time-series forecasting

* **Physics-Informed Neural Network (PINN)**
  Dissolved oxygen prediction based on physical constraints

* **Digital Twin**
  Environmental impact and scenario simulation


### Advanced Capabilities

* Explainable AI (XAI) dashboard with feature importance
* What-if analysis for policy and environmental scenarios
* Multi-role access (Public, Government, Researcher, Admin)
* Real-time alerts based on threshold violations
* Location-based comparison and benchmarking
* Automated PDF report generation


## Live Demo

Dashboard URL:
[https://pravaah-8ubxbo9e4ssm9okxtagnye.streamlit.app/](https://pravaah-8ubxbo9e4ssm9okxtagnye.streamlit.app/)

Demo Access:
Select any user role from the sidebar (no authentication required for demo).


## Installation & Setup

### Prerequisites

* Python 3.8 or higher
* pip
* Virtual environment (recommended)

### Steps

```bash
# Clone the repository
git clone https://github.com/Mayurr1804/Pravaah.git
cd Pravaah


# Create virtual environment
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
```

## Model Performance

| Model         | Metric        | Score    |
| ------------- | ------------- | -------- |
| YOLOv8        | mAP@0.5       | 94.2%    |
| Raman ML      | F1-Score      | 91.8%    |
| Random Forest | Test Accuracy | 94.0%    |
| PINN          | R² Score      | 0.90     |
| Prophet       | MAE           | ±2.5 WQI |


## Project Structure

```
pravaah/
│
├── app.py                # Main Streamlit application
├── requirements.txt      # Python dependencies
│
├── views/                # Dashboard UI components
├── models/               # Trained ML/DL models
├── utils/                # Utilities (XAI, simulations, helpers)
├── apis/                 # External API integrations
├── maps/                 # Geographic and spatial mapping
├── pipeline/             # Automated data workflows
├── data/                 # Datasets
├── config/               # Configuration files
└── outputs/              # Generated reports and outputs
```


## User Roles

* **Public**
  Basic detection, visualization, and awareness tools

* **Government**
  Policy-focused insights, XAI explanations, and what-if simulations

* **Researcher**
  Full analytics, model evaluation, and comparative analysis

* **Admin**
  System monitoring and configuration management


## Technology Stack

### Machine Learning & AI

* PyTorch
* scikit-learn
* YOLOv8
* Prophet

### Web & Visualization

* Streamlit
* Plotly
* Folium

### Data Processing

* pandas
* NumPy
* OpenCV


## Team

* **Aadrika Gupta** – Project Lead
* **Sangyan Hari Pushkar** – Team Member
* **Mayur Mundada** – Team Member

## Contact

* Email: [bt24eci005@iiitn.ac.in](mailto:bt24eci005@iiitn.ac.in)
* GitHub: [https://github.com/Mayurr1804](https://github.com/Mayurr1804)


If you find this project useful, consider starring the repository.
