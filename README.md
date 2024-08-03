# AML Transaction Monitoring System

## Project Overview

This project aims to develop a transaction monitoring system to identify potentially fraudulent transactions based on historical data. The system preprocesses data, applies machine learning models for anomaly detection, and provides insights and alerts for suspicious activities.

## Problem Statement

Develop a transaction monitoring system that:
    * Identifies potentially fraudulent transactions based on historical data.
    * Preprocesses and cleanses data.
    * Applies machine learning models to detect anomalies.
    * Provides insights and alerts for suspicious activities.

## Project Structure

AML_Transaction_Monitoring/
├── nifi-config/ # Apache NiFi configuration files
├── spark-scripts/ # Apache Spark scripts for data processing and ML models
├── flask-api/ # Flask API for interaction with Spark jobs
├── airflow-dags/ # Apache Airflow DAGs for orchestrating workflows
├── docker/ # Docker configurations (Dockerfile, docker-compose.yml)
├── data/ # Data storage (datasets, outputs)
├── notebooks/ # Jupyter Notebooks for data analysis and ML models
└── README.md # Project documentation


## Setup and Installation

1. **Clone the Repository:**
    - ```bash
    - git clone https://github.com/07priyayadav/AML_Transaction_Monitoring.git
    - cd AML_Transaction_Monitoring

2. Set Up a Virtual Environment:
    - python -m venv venv
    - source venv/bin/activate

3. Install Dependencies:
    - pip install -r requirements.txt

4. Configure Apache NiFi:
    * Place your NiFi configuration files in the nifi-config/ directory.
    * Follow NiFi setup instructions to deploy the configurations.

5. Set Up Apache Airflow:
    * Create and configure your Airflow DAGs in the airflow-dags/ directory.
    * Follow Airflow setup instructions to deploy your DAGs.

6. Build Docker Containers:
    * Use the provided Docker configurations in the docker/ directory.
    * Build and run Docker containers as follows:
        - docker-compose up --build

7. Run Spark Jobs:
    * Develop and execute Spark scripts located in the spark-scripts/ directory.
    
8. Start the Flask API:
    * Navigate to the flask-api/ directory and start the Flask server:
        python app.py

9. Work with Jupyter Notebooks:
    * Use the notebooks in the notebooks/ directory for data analysis and model development.
    * Start Jupyter Notebook server:
        jupyter notebook

# Usage

    * ETL Processing: Utilize Apache NiFi for data ingestion, transformation, and loading.
    * Data Processing: Run Spark jobs to preprocess data and apply machine learning models.
    * API Interaction: Use the Flask API to interact with the system and trigger processes.
    * Workflow Orchestration: Manage workflows using Apache Airflow.
    * Monitoring and Analysis: Explore and analyze data using Jupyter Notebooks.

# Contributing

    Contributions are welcome! Please submit issues or pull requests through the GitHub repository.