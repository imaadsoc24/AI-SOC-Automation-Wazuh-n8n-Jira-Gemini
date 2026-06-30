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
