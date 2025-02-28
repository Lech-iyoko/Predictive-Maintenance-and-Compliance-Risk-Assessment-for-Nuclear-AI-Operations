# Hackafuture-Transforming-Nuclear-Operations-with-AI

# Predictive Maintenance and Compliance Risk Assistant for Nuclear AI Operations

## Overview

The Predictive Maintenance & Compliance Assistant is an AI-powered system designed for predictive maintenance, tool criticality risk prediction, and compliance regulation checking in nuclear AI operations. Using cutting-edge technologies like XGBoost, Random Forest, LSTM, SHAP, and FastAPI, this system predicts failures in real-time, generates insightful reports, and ensures compliance with regulations.

Engineers can leverage this system to identify critical issues before failure occurs, assess tool reliability, generate maintenance recommendations, and validate compliance requirements efficiently and accurately.

## Key Features
  ✅ Real-time Failure Prediction: Uses advanced XGBoost and LSTM models to predict potential failures before they occur.
  
  ✅ Tool Criticality Risk Assessment: Evaluates the criticality of different tools based on multiple operational parameters.
  
  ✅ Compliance Regulation Checking: Automatically checks system compliance against predefined regulatory standards.
  
  ✅ SHAP-based Explainability: Engineers can visualize feature importance and understand how predictions are made.
  
  ✅ Scalability & Adaptability: The system is designed to be easily scalable and can integrate with different sensor data sources.
  
  ✅ FastAPI Integration: Provides a RESTful API for real-time prediction and compliance checking.
  
  ✅ Automated Report Generation: Generates detailed maintenance and compliance reports.
  
  ✅ Efficient & Sustainable: Optimized for handling large datasets efficiently, ensuring smooth AI-driven maintenance and monitoring.

## System Architecture
The system consists of:
  - Backend API (FastAPI) – Handles predictive maintenance and compliance verification.
  - Machine Learning Models:
    - XGBoost Model: Predicts failure probabilities.
    - NLP Model: Ensures regulatory compliance of maintenance actions.
    - Frontend Dashboard – For real-time monitoring and visualization.

## Setup Instructions
  1. Clone the Repository
     * git clone https://github.com/your-username/Predictive-Maintenance-and-Compliance-Assistant.git
     * cd Predictive-Maintenance-and-Compliance-Assistant
  2. Set Up a Virtual Environment
     * python -m venv env
     * source env/bin/activate  # On Windows use `env\Scripts\activate`
  3. Install Dependencies
     * pip install -r requirements.txt
  4. Run the Backend API
     * uvicorn main:app --reload

## Usage
  1. Train the Models
  - Run the training script to train XGBoost, Random Forest, and LSTM models:
    - This will save the trained models for real-time inference.
  
  2. Start the FastAPI Server
  - Run the FastAPI backend to serve predictions and compliance checks:
    - uvicorn app.main:app --reload
  
  The API will be available at http://127.0.0.1:8000/docs.
  
  3. Predict Failures & Check Compliance
  - Use the provided API endpoints to get real-time predictions and compliance checks.
  Example request:
    - curl -X POST "http://127.0.0.1:8000/predict" -H "Content-Type: application/json" -d '{ "torque": 50, "speed": 1500, "wear": 200, "temperature": 300 }'
  
  4. Generate Reports
  - Run the script to generate detailed reports or use the dashboard

## Future Enhancements
  * Integration with IoT Sensors for real-time data streaming.
  * Enhanced Compliance Auditing with machine learning-driven rule analysis.
  * Dashboard for Engineers to visualize trends and compliance violations.

## Contributors
  * Anant Raj - Developer & AI Engineer
  * Ananth P - UI Design Integration and Demo Video Editor
  * Alechenu Iyoko - Backend/API Development and Model Integration

Contributions Welcome! Feel free to open an issue or submit a pull request.

![image](https://github.com/user-attachments/assets/e99a038c-4d98-435d-a0b2-4a7bb1eee208)

<img width="1033" alt="Screenshot 2025-02-10 at 19 52 38" src="https://github.com/user-attachments/assets/e642b1a4-581f-403a-af79-2bd4e2554e25" />

<img width="1018" alt="Screenshot 2025-02-10 at 19 52 06" src="https://github.com/user-attachments/assets/95955673-3e38-4578-b93f-8503316cdeed" />

Demo Video: https://drive.google.com/file/d/1ozEmajSfJfI0BTWapqkpX7UEdS2ZHl3D/view?usp=sharing
