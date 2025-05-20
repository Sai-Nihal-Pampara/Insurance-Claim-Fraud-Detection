# 🚗 Car Insurance Claim Processing Using Machine Learning

## 📌 Overview

Efficient claim processing is crucial for delivering high customer satisfaction and maintaining operational excellence in the insurance sector. 
Traditional claim processing systems rely heavily on manual checks and rule-based decision-making, which are time-consuming, error-prone, and often inconsistent.

This project leverages **Machine Learning (ML)**—specifically **Logistic Regression**—to streamline the claim classification process. 
By automating decision-making, insurers can detect fraudulent claims more accurately, process genuine claims faster, and scale operations seamlessly.

## 🔍 Problem Statement

Traditional methods struggle with:
- Manual and repetitive tasks
- High error rates and delayed decisions
- Elevated costs and limited scalability

Our goal is to build a machine learning-based system that improves:
- ✅ Accuracy in claim classification
- ⚡ Speed of processing
- 📈 Scalability of operations
- 🔒 Fraud detection reliability

## 🧠 Why Logistic Regression?

Among various ML algorithms suitable for binary classification (e.g., fraud vs. genuine), **Logistic Regression** stands out for its:
- Simplicity and interpretability
- Strong performance with categorical outcomes
- Speed and efficiency in training and inference


## 📊 Dataset & Model

- The dataset consists of historical claim records with features such as claim amount, policy details, customer demographics, and fraud labels.
- Preprocessing includes handling missing values, encoding categorical variables, and feature scaling.
- The logistic regression model is trained to classify claims as **fraudulent (1)** or **genuine (0)**.


## 📁 Folder Structure

car-insurance-ml/
├── data/ # Raw and processed datasets
│ └── claims.csv
├── notebooks/ # Jupyter notebooks for EDA and modeling
│ └── model_training.ipynb
├── models/ # Saved model artifacts
│ └── logistic_model.pkl
├── scripts/ # Python scripts for preprocessing, training, etc.
│ ├── train.py
│ ├── predict.py
│ └── utils.py
├── results/ # Evaluation results and graphs
├── README.md # Project documentation
└── requirements.txt # Python dependencies


# Insurance Claim Detection Web App

A real‐time insurance claim detection system with a FastAPI backend and React frontend.

## Table of Contents

- [Overview](#overview)  
- [Prerequisites](#prerequisites)  
- [Installation](#installation)  
  - [Backend](#backend)  
  - [Frontend](#frontend)  
- [Running the Project](#running-the-project)  
- [Troubleshooting](#troubleshooting)  
- [Contributing](#contributing)  
- [License](#license)  

## Overview
This repository contains a full‐stack application for detecting the likelihood of insurance claim fraud. The backend is powered by FastAPI and exposes prediction endpoints, while the frontend is built with React to provide a user‐friendly interface.

## Prerequisites
- **Python**
- **Node.js & npm**  
- **Git** (for cloning the repo)  

## Installation
Clone this repository and install dependencies for both the backend and frontend.

git clone https://github.com/your-username/insurance-claim-detection.git
cd insurance-claim-detection

Backend
Navigate to the backend folder:
cd backend_folder

(Optional) Create and activate a virtual environment:
python3 -m venv venv
source venv\Scripts\activate        # Windows

Install Python dependencies:
pip install -r requirements.txt

Frontend
Navigate to the React app folder:
cd web
Install Node.js modules:

npm install
Running the Project
Once all dependencies are installed, start both servers in separate terminals.

To Start the Backend
cd backend_folder
python -m uvicorn app:app --reload
The API will be available at http://localhost:8000/.

To Start the Frontend
cd web
npm start
The React app will open at http://localhost:3000/ by default.

Tip: Make sure both servers are running simultaneously so that the frontend can communicate with the backend without interruption.

Troubleshooting
Port conflicts: If 8000 or 3000 is in use, you can specify a different port:
uvicorn app:app --reload --port 8001
npm start -- --port 3001

Dependency issues:
Ensure you’re using compatible versions of Python and Node.js.
Delete node_modules/ and run npm install again if frontend modules fail to load.
Recreate your virtual environment and reinstall Python packages if you run into import errors.

## **Contributing?**
Feel free to fork this repo, create feature branches, and submit pull requests. Contributions are welcome
Create a feature branch (git checkout -b feature/xyz)
Commit your changes (git commit -m "Add feature XYZ")
Push to your branch (git push origin feature/xyz)
Open a Pull Request
Please follow the existing code style and include clear commit messages.

## **Key Takeaways**
ML-based claim processing significantly outperforms traditional methods.
Logistic Regression offers a practical and effective approach for binary fraud detection.
The system can be easily scaled and integrated into real-world insurance workflows.

## **References**
Scikit-learn Documentation
Machine Learning Mastery – Logistic Regression
Kaggle: Insurance Claim Datasets
Aczel & Sounderpandian, Complete Business Statistics

## **Contact**
For any queries or collaborations, reach out via sainihal.pampara@gmail.com, gopidhanavath1@gmail.com, deysujoy28@gmail.com or raise an issue in the repo.


