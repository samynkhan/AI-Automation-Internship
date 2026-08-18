# 🤖 AI Automation Internship — Tasks Portfolio

**Intern:** Hafiz Ahmad Raza  
**Repository:** `AI-Automation-Internship`  

---

## 📌 Repository Overview
This repository contains all internship tasks, workflow automation pipelines, database configurations, and submission reports completed during the internship program.

---

## 🚀 Day 03: Google Sheets & n8n Workflow Integration

### 📝 Overview
An automated workflow designed to read data from Google Sheets, process JSON transformations using n8n, and log automated records.

### ⚙️ Workflow Architecture
`Google Sheets` ➔ `n8n Trigger / Read Node` ➔ `JSON Data Transformation` ➔ `Output Action`

### 📁 Deliverables (`/Day-03`)
* **`/Google Sheets`**: Form responses and sheet integration setup.
* **`/n8n`**: Workflow configuration and JSON structure.
* **`/Postman`**: API requests and Webhook testing payloads.
* **`/Report`**: Task execution report.

---

## 🚀 Day 05: Automated Student Registration Pipeline

### 📝 Overview
An end-to-end automated pipeline using **n8n** that captures student registrations via **Google Forms**, auto-populates structured records in **Notion Database**, and posts real-time alerts to a **Slack** channel (`#n8n-alerts`).

### ⚙️ Workflow Architecture
`Google Form / Sheet` ➔ `n8n Google Sheets Trigger` ➔ `Notion Database Entry` ➔ `Slack Webhook Alert`

### 🛠️ Key Implementations
* **Google Sheets Trigger:** Listens for incoming registration rows.
* **Notion Integration:** Dynamically populates student details (`Full Name`, `Email`, `Course`) with status `New`.
* **Slack Webhook Notifications:** Utilized HTTP Request POST node to send formatted alerts directly to Slack.

### 📁 Deliverables (`/Day 5`)
* **`/n8n`**: `Task_05 (Slack + Notion + Forms).json` workflow export & execution screenshots.
* **`/Notion`**: Screenshot of the updated `Student Registration` database.
* **`/Slack`**: Screenshot of the delivered notification in `#n8n-alerts`.
* **`/Report`**: PDF report of the task completion.

---

## ⚙️ How to Run / Import Workflows
1. Open your **n8n** workspace.
2. Click **Import from File** in the workflow editor menu.
3. Select the `.json` file from the respective task directory (`/Day-03/n8n` or `/Day 5/n8n`).
4. Re-configure API credentials (Notion, Google Sheets, Slack Webhooks) and activate the workflow.
