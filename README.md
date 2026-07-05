# AI Energy Management Agent for Educational Institutions and Workplaces

## AICTE Generative AI & Agentic System Engineering Internship

### SDG 13 – Climate Action

---

## Project Overview

The AI Energy Management Agent is an AI-powered intelligent system designed to monitor and analyze energy consumption in educational institutions and workplaces. It uses Google Gemini AI to generate intelligent insights, detect high energy consumption areas, estimate carbon emissions, and provide practical energy-saving recommendations.

The project also demonstrates Agentic AI automation using n8n by automatically generating AI-powered institutional energy management reports and sending them via Gmail.

---

## Problem Statement

Educational institutions and workplaces consume large amounts of electricity through classrooms, laboratories, computer labs, hostels, offices, cafeterias, and other facilities. Inefficient energy usage increases electricity costs and carbon emissions. Without proper monitoring and AI-driven analysis, organizations struggle to identify energy wastage and implement sustainable energy management practices.

---

## Proposed Solution

The AI Energy Management Agent:

- Monitors institutional energy consumption
- Detects high energy consumption areas
- Estimates carbon emissions
- Uses Google Gemini AI for intelligent energy analysis
- Generates energy-saving recommendations
- Supports SDG 13 – Climate Action
- Simulates real-time energy monitoring
- Automatically emails AI-generated reports using n8n

---

## Technologies Used

- Python
- Google Colab
- Google Gemini API (`google-genai`)
- Pandas
- NumPy
- Matplotlib
- n8n
- Gmail Integration
- GitHub

---

## Features

- Institutional Energy Dataset
- Energy Consumption Visualization
- AI Energy Consumption Analysis
- High Energy Consumption Detection
- Carbon Emission Estimation
- Smart Energy Alerts
- Real-Time Energy Monitoring Simulation
- AI-generated Institutional Energy Management Report
- Agentic AI Workflow using n8n
- Automatic Email Notification

---

## Project Architecture

```text
                    +----------------------+
                    | Institution/User     |
                    +----------+-----------+
                               |
                               v
                 +---------------------------+
                 |   Google Colab Notebook   |
                 +---------------------------+
                 | Institutional Dataset     |
                 | Data Visualization        |
                 | Carbon Emission Analysis  |
                 | AI Analysis (Gemini)      |
                 | Report Generation         |
                 +------------+--------------+
                              |
                              | GitHub
                              v
                 +---------------------------+
                 |       n8n Workflow        |
                 +---------------------------+
                 | Manual Trigger            |
                 | Institutional Energy Data |
                 | Calculate Total Energy    |
                 | Google Gemini AI          |
                 | Gmail Report              |
                 +------------+--------------+
                              |
                              v
                     +-----------------------+
                     | Institution/User      |
                     | Receives AI Report    |
                     +-----------------------+
```

---

## n8n Workflow

```text
Manual Trigger
      │
      ▼
Institutional Energy Data
      │
      ▼
Calculate Total Energy
      │
      ▼
Google Gemini AI
      │
      ▼
Generate AI Report
      │
      ▼
Send Report via Gmail
```

---

## Project Workflow

```text
Google Colab
↓
Institutional Energy Dataset
↓
Energy Visualization
↓
High Energy Consumption Detection
↓
Carbon Emission Estimation
↓
Gemini AI Analysis
↓
AI Energy Management Report
↓
GitHub

n8n
↓
Manual Trigger
↓
Institutional Energy Data
↓
Calculate Total Energy
↓
Google Gemini AI
↓
Generate AI Report
↓
Send Report via Gmail
```

---

## Future Scope

- IoT Smart Meter Integration
- Live Energy Monitoring Dashboard
- Building-wise Energy Analytics
- Carbon Footprint Dashboard
- Renewable Energy Integration
- Predictive Energy Consumption using AI
- Mobile Notifications
- Smart Campus Energy Management

---

## Project Files

```text
AI-Energy-Management-Agent/
│
├── AI_Energy_Management_Agent.ipynb
├── Institutional_Energy_Report.txt
├── README.md
├── requirements.txt
└── screenshots/
    ├── colab_notebook.png
    ├── energy_visualization.png
    ├── ai_report.png
    ├── n8n_workflow.png
    └── gmail_output.png
```

---

## Author

Name Here

AICTE Generative AI & Agentic System Engineering Internship Project
