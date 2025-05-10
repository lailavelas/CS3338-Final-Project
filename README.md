# CS3338-Final-Project
We as a group worked on this together.
There should be separate folder's with the required documents, files requested for the final project. 
Along with any documents, files that are required to run them.

# Machine Learning Platform for Intelligent Water Systems Management

## Table of Contents
- [Introduction](#introduction)
- [Jira Link](#jira-link)
- [Formal Objective Breakdown](#formal-objective-breakdown)
- [Goals and Importance](#goals-and-importance)
- [Installation and Setup](#installation-and-setup)
- [User Interface Guide](#user-interface-guide)
- [Usage Instructions](#usage-instructions)
- [Troubleshooting](#troubleshooting)
- [Appendix](#appendix)
- [LaTeX Documentation](#latex-documentation)
- [Authors](#authors)

---

## Introduction
This platform allows users to monitor water consumption, detect anomalies, and optimize water usage through real-time data visualization and predictive analytics.

---

## Jira Link
Access the Jira board for project management and sprint planning here: [Jira Board](https://csula-kv.atlassian.net/jira/software/projects/WSM/boards/6)

---

## Formal Objective Breakdown
The primary objectives of this platform are:
- Real-time monitoring of water consumption
- Automated alerts for leak detection
- Predictive analysis for maintenance
- Detailed analytics for optimizing water usage

---

## Goals and Importance
This platform is designed to bridge the gap in water consumption monitoring by providing:
- Enhanced water usage efficiency
- Early detection of leaks to prevent waste
- Data-driven insights for better resource management

By offering real-time monitoring and predictive analytics, it empowers municipalities and property owners to optimize water consumption and reduce waste.

---

## Installation and Setup

### System Requirements
- Docker (latest version)
- Node.js (for frontend)
- SQL Database

### Installation Steps
1. Clone the repository from GitHub:
   ```bash
   git clone https://github.com/your-username/your-repo.git

Navigate to project directory: cd your-repo

Run Docker Composed to initialize all services: docker-compose up

Open the application at http://localhost:5000.
Docker Configuration
The Docker setup includes:

Frontend: React-based dashboard
Backend: Flask for API management
Database: SQL instance for data storage

User Interface Guide

Dashboard Overview
- Real-time water consumption data
- Alerts for abnormal usage
- System health status

Analytics Page
- Graphical representation of historical data
- Comparative analysis of water usage trends

Settings
- Sensor configurations
- Alert preferences

Reports
- Generate and export reports in CSV or PDF formats

Usage Instructions

Logging In
1. Open the application at http://localhost:5000.
2. Enter your username and password.
3. Click Login.

Viewing Data
- Navigate to the Dashboard to see live metrics.

Configuring Alerts
- Go to Settings and enable notifications for high usage or leaks.

Generating Reports
- Click on Reports and select the time range for data.

Troubleshooting

Common Issues
- Docker container not starting → Verify Docker installation and run:
docker-compose up --build
- Dashboard not loading → Clear browser cache and retry.

Error Messages
- 500 Internal Server Error → Restart Docker containers.
- 404 Not Found → Check Docker logs for missing dependencies.

Appendix

API Documentation
Refer to the API endpoints for detailed usage.

Database Schema
SQL-based with normalized tables for optimized querying.

Authors

Robert Castro
Calvin Chau
Yvan Michel Kemsseu Yobeu
Laila Velasquez
Kassandra Vera
