# Bio-Inspired Autonomous Building Health and Energy Management System Using AI-ML Systems

[![Forks](https://img.shields.io/github/forks/G-Danush/Bio-Inspired-Autonomous-Building-Health-and-Energy-Management-System-Using-AI-ML-Systems?style=for-the-badge)](https://github.com/G-Danush/Bio-Inspired-Autonomous-Building-Health-and-Energy-Management-System-Using-AI-ML-Systems/network/members)
[![Stars](https://img.shields.io/github/stars/G-Danush/Bio-Inspired-Autonomous-Building-Health-and-Energy-Management-System-Using-AI-ML-Systems?style=for-the-badge)](https://github.com/G-Danush/Bio-Inspired-Autonomous-Building-Health-and-Energy-Management-System-Using-AI-ML-Systems/stargazers)
[![Issues](https://img.shields.io/github/issues/G-Danush/Bio-Inspired-Autonomous-Building-Health-and-Energy-Management-System-Using-AI-ML-Systems?style=for-the-badge)](https://github.com/G-Danush/Bio-Inspired-Autonomous-Building-Health-and-Energy-Management-System-Using-AI-ML-Systems/issues)
[![License](https://img.shields.io/github/license/G-Danush/Bio-Inspired-Autonomous-Building-Health-and-Energy-Management-System-Using-AI-ML-Systems?style=for-the-badge)](https://github.com/G-Danush/Bio-Inspired-Autonomous-Building-Health-and-Energy-Management-System-Using-AI-ML-Systems/blob/main/LICENSE)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

![Machine Learning](https://img.shields.io/badge/Machine_Learning-000000?style=for-the-badge&logo=openai&logoColor=white)
![Deep Learning](https://img.shields.io/badge/Deep_Learning-00599C?style=for-the-badge&logo=keras&logoColor=white)
![IoT](https://img.shields.io/badge/IoT_&_Smart_Sensors-007ACC?style=for-the-badge)

## 📌 Overview
This repository contains a bio-inspired autonomous building health and energy management framework. The system integrates artificial immune system principles with machine learning and deep learning techniques to perform adaptive anomaly detection and intelligent monitoring of smart infrastructure. By continuously analyzing environmental, operational, and structural parameters, the system identifies complex fault conditions in real-time.

## 👥 Team
This project was developed at the **Indian Institute of Information Technology Sri City (IIIT Sri City)** under the guidance of **Dr. Sakthi Swarrup J**.
* **Danush Guntupalli** (OMIO25S00020)
* **Nagaraju Marella** (OMIO25500030)
* **Saba Afreen Khatoon** (OMIO25S00045)

## ⚠️ Problem Statement
Modern smart infrastructure continuously generates vast amounts of environmental and structural data. Traditional monitoring systems rely primarily on static thresholds and analyze parameters in isolation. This leads to:
* High false alarm rates and delayed anomaly detection.
* Poor adaptability under dynamic environmental conditions.
* Inability to identify complex, multi-condition correlated faults.

## 🧠 System Architecture
The framework is built on a multi-layer intelligent architecture inspired by biological immune systems:
* **Data Simulation Layer:** Generates realistic synthetic multi-sensor streams (temperature, humidity, occupancy, vibration, strain, energy consumption).
* **Data Processing Layer:** Handles missing values, normalization, scaling, noise reduction, and outlier clipping.
* **Immune Intelligence Layer:**
  * **Innate System:** Rule-based immediate anomaly analysis using expert conditions.
  * **Adaptive System:** Machine learning-based detection integrating Isolation Forest and Autoencoder models.
* **Multi-Issue Fusion Layer:** Combines outputs from multiple models and sensor streams to identify correlated fault conditions.
* **Decision Layer:** Generates alerts, risk classifications, and corrective recommendations autonomously.
* **Memory Layer:** Stores historical anomalies and past decisions for continuous adaptive learning.

## 🚀 Methodology & Models
* **Isolation Forest:** Used for unsupervised statistical anomaly detection via random partitioning trees. 
* **Autoencoder:** Deep neural networks utilized for nonlinear anomaly detection through reconstruction error analysis.
* **Hybrid Fusion:** Anomaly predictions from the Autoencoder, Isolation Forest, and rule-based checks are combined using weighted anomaly fusion techniques to produce a finalized risk score.

## 📊 Performance & Results
The proposed system was evaluated on synthetic datasets containing realistic structural and environmental anomalies. The hybrid framework demonstrated strong adaptability and significantly reduced false alarms compared to standalone models. 

**Key Metrics:**
* **Accuracy:** 82.2%
* **Precision:** 86.2%
* **Recall:** 69.9%
* **F1-Score:** 77.2%
* **ROC-AUC Score:** 0.89
* **False Alarm Rate:** ~8.4%

## 🛠️ Tech Stack
The project is entirely software-based and implemented using the following tools and libraries:
* **Language:** Python
* **Data Manipulation:** NumPy, Pandas
* **Machine Learning:** Scikit-learn (Isolation Forest)
* **Deep Learning:** TensorFlow (Autoencoders)
* **Visualization & Web App:** Matplotlib, Streamlit

## 🔮 Future Work
Future enhancements to scale and improve this architecture include:
* Real-time IoT sensor integration and Edge AI deployment.
* Application of Reinforcement Learning and Transformer-based anomaly detection.
* Explainable AI (XAI) integration and Federated learning.
* Digital twin implementation for smart city infrastructure monitoring.
