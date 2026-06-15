# 🤖 Automated Data Request Ticketing Pipeline (Power Automate)

## 🎯 Business Problem

The business analytics team receives daily custom report requests via disorganized channels (emails, Slack messages, chats), leading to lost requirements, missing context, and zero visibility into operational data backlogs.

## ⚙️ Workflow Architecture

I designed an automated cloud orchestration workflow using the **Microsoft Power Automate Platform** and the **GitHub Developer Connector**:

1. **The Entry Trigger:** Business stakeholders complete a structured data request form via **Microsoft Forms**.

2. **Data Extraction & Logic parsing:** Power Automate catches the submission, sanitizes string entries, and formats a JSON payload.

3. **API Dispatch:** The system initiates an authentication handshake with the repository and posts structural metadata, creating a live, assigned **GitHub Issue** automatically.

## 📁 Repository Contents

- `workflow-logic/`: Visual pipeline map and workflow json blueprints.
 
