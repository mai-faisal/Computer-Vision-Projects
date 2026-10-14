
# Kidney Disease Classification End-to-End MLOps Project

An end-to-end deep learning project designed to classify kidney diseases (such as Tumor, Normal, Cyst, and Stone) using Computer Vision and Convolutional Neural Networks (CNN), structured following standard MLOps best practices and deployed via a local Flask web interface.

---

## 🚀 Project Overview

This project transitions a raw Jupyter Notebook machine learning experiment into a robust, modular, and production-ready pipeline. It automates every stage of the machine learning lifecycle—from data ingestion and validation to model training, evaluation, and web deployment.

---

## 🛠️ Project Structure

The repository is organized following clean architecture principles:

```text
├── artifacts/             # Stores intermediate data, models, and evaluation metrics
├── config/                # Configuration files (config.yaml)
├── src/
│   ├── cnnClassifier/
│   │   ├── components/    # Modular pipeline stages (Ingestion, Training, Evaluation, etc.)
│   │   ├── config/        # Configuration management
│   │   ├── entity/        # Data structures and configuration entities
│   │   ├── pipeline/      # Execution pipelines for training and prediction
│   │   └── utils/         # Helper functions (file handling, logging, etc.)
├── templates/             # HTML templates for the web interface
├── app.py                 # Flask web application for local deployment
├── main.py                # Main script to execute the end-to-end pipeline
├── params.yaml            # Model hyperparameters (Epochs, Batch Size, etc.)
├── requirements.txt       # Project dependencies
└── README.md              # Project documentation


⚙️ Key Features
Modular Pipeline Architecture: Separated concerns into distinct components for high maintainability.
Config-Driven Development: Centralized parameters and paths using YAML configuration files (config.yaml and params.yaml).
Deep Learning Model: Built using TensorFlow/Keras with custom CNN architectures / Transfer Learning for image classification.
Interactive Web Application: A user-friendly Flask web UI allowing users to upload kidney scan images and instantly receive diagnostic predictions locally without internet dependency.
💻 Getting Started & Installation
Follow these steps to set up and run the project locally on your machine:
1. Clone the repository
git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
cd YOUR_REPOSITORY_NAME


2. prerequisites:
    python=3.10 -y



3. Install dependencies
pip install -r requirements.txt


4. Run the training pipeline
python main.py


5. Launch the Web Application
python app.py


Open your browser and navigate to: http://127.0.0.1:8080
📊 Author
Developed as part of an advanced Computer Vision & MLOps project to demonstrate real-world deployment capabilities.


