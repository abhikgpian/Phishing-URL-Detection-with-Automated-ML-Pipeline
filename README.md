## Phishing URL Detection with Automated ML Pipeline
Welcome to the Phishing URL Detection project! This repository implements a robust and scalable automated machine learning pipeline designed to detect phishing and malicious URLs with high precision. Built for efficiency and scalability, this solution integrates advanced data processing, machine learning, and API services to streamline threat detection workflows.

## Features
### Comprehensive Feature Schema
Designed with over 30+ carefully engineered features to ensure precise identification of phishing and malicious URLs. The schema covers multiple aspects of URL structure and behavior, enabling accurate classification and detection.
### Automated Data Pipeline
Seamlessly handles data ingestion, validation, and transformation to ensure consistent and clean inputs for the ML models. The preprocessing stage automates feature extraction and data normalization, reducing manual intervention and potential errors.
### Robust Logging and Monitoring
Implements detailed logging with timestamped log files to track every stage of the pipeline. This significantly enhances debugging, monitoring, and issue resolution, providing clear insights into pipeline health and performance.
### Scalable FastAPI Service
Developed a high-performance FastAPI service that integrates with MongoDB to serve real-time predictions. This service supports continuous pipeline execution and model updates, enabling rapid threat detection in production environments.
### Versatile Output Formats
Generated structured prediction outputs in both CSV and HTML formats, improving model interpretability and accessibility for end-users and stakeholders.


## Getting Started
### Prerequisites:-
1.Python 3.8+
2.MongoDB instance (local or cloud)
3.FastAPI
4.Relevant Python libraries (see requirements.txt)

## Installation
### 1.Clone the repository:git clone https://github.com/yourusername/phishing-url-detection.gitcd phishing-url-detection
### 2.Install dependencies:pip install -r requirements.txt
### 3.Set up MongoDB and update connection details in config.py.

## Running the Service
Start the FastAPI server:-http://localhost:8000/docs



