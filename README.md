Patient Readmission Prediction System (Group 13)
This web application uses a Random Forest machine learning model to predict early hospital readmission risks for diabetes patients. Built with Streamlit, it provides real-time risk assessments to help evaluate patient care post-discharge.

Live Application & Links:
Live Interactive Web App: https://group-13.streamlit.app/
GitHub Repository: https://github.com/Lu-guru

Project Architecture & Features:
•	Dataset: UCI Diabetes 130-US Hospitals dataset (1999–2008).
•	Model Engine: Tuned Random Forest classification model (random_forest_model.pkl).
•	Backend API: FastAPI application (main.py) for serving prediction endpoints.
•	Frontend UI: Streamlit interactive web application (app.py) for clinical risk evaluation.
•	Tracking & Logging: MLflow experiment tracking database (mlflow.db) and log runs (mlruns/).

Repository & Artifact Structure:
•	app.py — Streamlit Frontend Interface
•	main.py — FastAPI REST API Backend
•	random_forest_model.pkl — Tuned Model Binary
•	requirements.txt — Environment Dependencies
•	mlflow.db — MLflow SQLite Tracking DB
•	mlruns/ — MLflow Artifact Logs
•	README.md — Project Documentation

Developed by Group 13 — Capstone Portfolio Project

