# AI-Driven Fraud Detection and AML Compliance Platform

## Overview

This project aims to combat credit card fraud and enhance Anti-Money Laundering (AML) compliance using an advanced AI-driven analytics platform. The platform leverages a robust technology stack and sophisticated machine learning models to protect financial transactions, ensure regulatory compliance, and maintain customer trust.

## Features

- **Real-Time Fraud Detection:** Utilizes machine learning models to detect and prevent fraudulent activities as they occur.
- **AML Compliance:** Ensures adherence to evolving AML regulations through automated compliance reporting.
- **Advanced Analytics:** Employs deep learning and predictive analytics to identify fraud trends and patterns.
- **Comprehensive Data Handling:** Integrates data from various sources, processes it in real-time, and provides actionable insights.
- **User-Friendly Dashboard:** Real-time monitoring and analytics dashboard for operational teams to quickly respond to potential threats.

## Technology Stack

- **Apache Hadoop:** Foundation for resilient and scalable data storage.
- **Apache Kafka:** Central hub for real-time data processing.
- **Apache Spark:** High-speed processing for advanced analytics.
- **Apache HBase:** Real-time access to large datasets.
- **Neo4j:** Graph database for analyzing complex relationships.
- **Apache NiFi:** Robust data ingestion and flow automation.

## System Architecture

1. **Data Ingestion:** Apache NiFi automates the collection, transformation, and distribution of data.
2. **Data Processing:** Apache Kafka and Apache Spark handle real-time data processing and analytics.
3. **Data Storage:** Apache Hadoop and HBase provide scalable and reliable data storage.
4. **Complex Relationship Analysis:** Neo4j analyzes and visualizes connections between entities for AML investigations.
5. **Real-Time Monitoring:** A dashboard displays real-time data, highlighting anomalies and potential fraud for immediate action.

## Key Components

### Anomaly Detection Models

- Identify deviations from normal transaction patterns.
- Flag unusual activities in real-time for immediate intervention.

### Predictive Analytics

- Analyze past fraud cases to forecast future trends.
- Help anticipate and prevent fraud before it occurs.

### Compliance Reporting

- Automatically generate compliance reports.
- Adapt dynamically to changes in regulations.
- Simplify the auditing process with consistently formatted data.

## Implementation Strategy

1. **Pilot Project:** Test and validate the system in a controlled environment.
2. **Full-Scale Rollout:** Expand the implementation across the network after successful validation.

## Expected Benefits

- **Reduced Fraud Losses:** Effective prevention and detection of fraud.
- **Improved Compliance:** Decreased issues and penalties related to compliance.
- **Enhanced Customer Satisfaction:** Increased trust and confidence in security measures.

## How to Run the Project

### Prerequisites

- **Python 3.8+**
- **Apache Hadoop**
- **Apache Kafka**
- **Apache Spark**
- **Apache HBase**
- **Neo4j**
- **Apache NiFi**

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/fraud-detection-aml-compliance.git
    cd fraud-detection-aml-compliance
    ```

2. Set up the environment:
    ```sh
    python -m venv venv
    source venv/bin/activate
    ```

3. Install the required Python packages:
    ```sh
    pip install -r requirements.txt
    ```

### Running the Application

1. **Start Apache NiFi:** 
   ```sh
   nifi.sh start
