# AI Career Intelligence Platform

An AI-powered career intelligence platform that automatically discovers, analyzes, scores, prioritizes, and tracks job opportunities using automation, artificial intelligence, and workflow orchestration.

---

## Business Problem

The modern technology job market is highly fragmented.

Candidates must monitor dozens of career websites, manually review hundreds of job descriptions, research companies, evaluate role fit, track applications, and manage interview pipelines.

This process creates:

* Information overload
* Missed opportunities
* Inefficient application prioritization
* Lack of centralized tracking
* Significant time investment

As competition in the technology sector increases, job seekers need intelligent systems that help them focus on the highest-value opportunities.

---

## Solution

The AI Career Intelligence Platform automates the entire job discovery and evaluation workflow.

The platform continuously collects job opportunities from multiple sources, evaluates them using AI, enriches them with company intelligence, stores them in a centralized CRM, delivers daily alerts, and provides analytics dashboards for decision support.

---

## Business Value

The platform transforms job searching from a manual process into an AI-assisted decision-making system.

Benefits include:

* Reduced manual research
* Faster opportunity discovery
* Better application prioritization
* Improved interview pipeline management
* Centralized career intelligence repository
* Increased visibility into career opportunities

---

## Features

* Automated Job Discovery
* AI Job Matching
* Company Intelligence Enrichment
* Duplicate Prevention Engine
* Telegram Notifications
* Google Sheets CRM
* Dashboard Analytics
* Application Tracking
* Career Path Classification
* Match Scoring Engine

---

## Workflow

1. Scheduled execution starts daily at 08:00
2. Job data is collected from multiple Greenhouse APIs
3. Duplicate jobs are filtered
4. OpenAI evaluates each position
5. Match score and career fit are generated
6. Company intelligence is added
7. Results are stored in Google Sheets CRM
8. Top opportunities are delivered via Telegram
9. Dashboard metrics are updated automatically

---

## Architecture

```text
+----------------------+
| Greenhouse APIs      |
+----------------------+
           |
           v
+----------------------+
| n8n Workflow Engine  |
+----------------------+
           |
           v
+----------------------+
| OpenAI Analysis      |
+----------------------+
           |
           v
+----------------------+
| Company Intelligence |
+----------------------+
           |
           v
+----------------------+
| Google Sheets CRM    |
+----------------------+
           |
      +----+----+
      |         |
      v         v
 Telegram   Dashboard
```

---

## Current Capabilities

* 7 Greenhouse company integrations
* Automated daily execution
* AI-powered scoring engine
* Duplicate prevention system
* Telegram notification engine
* Google Sheets CRM
* Interactive analytics dashboard
* Company intelligence enrichment
* Application tracking workflow

---

## Tech Stack

* n8n
* OpenAI API
* Greenhouse API
* Google Sheets
* Telegram Bot API
* JavaScript

---

## Repository Structure

```text
AI-Career-Intelligence-Platform
│
├── README.md
│
├── docs
│   └── architecture.md
│
├── workflow
│   └── job-discovery-agent-workflow.json
│
└── screenshots
    ├── workflow.png
    ├── dashboard.png
    └── telegram.png
```

---

## Screenshots

### Workflow

Workflow orchestration and automation process.

### Dashboard

Analytics and KPI dashboard built on top of Google Sheets.

### Telegram Notifications

Daily AI-ranked job opportunity alerts.

---

## Future Roadmap

* Resume Matching Engine
* Salary Intelligence
* Auto Apply Tracking
* Power BI Dashboard
* Multi-Source Job Discovery
* LinkedIn Integration
* ATS Compatibility Analysis

---

## Author

Dor Sharabi

B.A. Business Administration & Information Systems

Focus Areas:

* Business Analysis
* Information Systems
* Automation
* Data Analytics
* AI Workflows
* Process Optimization
