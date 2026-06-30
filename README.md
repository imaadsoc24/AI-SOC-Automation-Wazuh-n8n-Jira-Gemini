# 🤖 AI-Powered SOC Automation with Wazuh, n8n, Jira & Google Gemini

> An end-to-end AI-driven Security Operations Center (SOC) automation workflow that automatically detects security alerts in Wazuh SIEM, enriches them with VirusTotal intelligence, analyzes them using Google Gemini AI, creates Jira incidents, stores investigation results in PostgreSQL, and sends email notifications to security analysts.

---

## 📌 Project Overview

Modern Security Operations Centers receive thousands of security alerts every day. Manual investigation of each alert is time-consuming and increases Mean Time To Respond (MTTR).

This project demonstrates how Security Operations can be automated using Wazuh SIEM, n8n, Google Gemini AI, VirusTotal, Jira, PostgreSQL, and Gmail.

The workflow automatically:

- Detects high-severity alerts from Wazuh SIEM
- Extracts Indicators of Compromise (IOCs)
- Performs VirusTotal reputation checks
- Generates an AI-powered investigation summary using Google Gemini
- Creates an incident in Jira
- Stores investigation details in PostgreSQL
- Sends an email notification to SOC analysts

This project simulates how a modern AI-assisted SOC can reduce manual effort while improving incident response efficiency.

---

# 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| SIEM | Wazuh |
| Automation | n8n |
| AI | Google Gemini |
| Threat Intelligence | VirusTotal |
| Ticketing | Jira |
| Database | PostgreSQL |
| Email Notifications | Gmail SMTP |
| Operating System | Ubuntu Linux |
| Containerization | Docker |
| Version Control | Git & GitHub |

---

# 🏗️ Workflow Architecture

The automation workflow follows the sequence below:

1. Wazuh detects a high-severity security alert.
2. The alert is sent to n8n using a Webhook.
3. n8n extracts important IoCs (IP address, hash, domain, etc.).
4. VirusTotal checks the reputation of the extracted IoCs.
5. Google Gemini AI analyzes the alert and generates an investigation summary.
6. A Jira incident ticket is created automatically.
7. Investigation details are stored in PostgreSQL.
8. A notification email is sent to the SOC analyst.
9. The analyst reviews the Jira ticket and takes further action.

---

# ✨ Key Features

- 🚨 Automated alert ingestion from Wazuh SIEM
- 🔍 Automatic IoC extraction (IP, Domain, URL, Hash)
- 🌐 VirusTotal threat intelligence enrichment
- 🤖 AI-powered investigation using Google Gemini
- 🎫 Automatic Jira incident creation
- 🗄️ PostgreSQL database storage for investigations
- 📧 Email notification to SOC analysts
- ⚡ End-to-end no-code automation using n8n
- 📊 Reduced Mean Time To Detect (MTTD) and Mean Time To Respond (MTTR)
- 🔒 Suitable for Blue Team and SOC automation demonstrations

---

# 📂 Project Structure

```text
AI-SOC-Automation-Wazuh-n8n-Jira-Gemini/
│
├── README.md
├── LICENSE
├── AI-SOC-Automation-Workflow-SOP.docx
│
└── screenshots/
    ├── 01-n8n-workflow-overview.png
    ├── 02-wazuh-high-severity-alert.png
    ├── 03-jira-case-created.png
    ├── 04-ai-investigation-comment.png
    ├── 05-email-notification.png
    ├── 06-ai-investigation-report.png
    ├── 07-postgresql-incident-database.png
    ├── 08-final-n8n-workflow.png
    └── ...
```

---


