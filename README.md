# ai-monthly-budget-automation
AI-driven monthly budget automation built using n8n from a QA perspective
# AI Automation for Monthly Budget (n8n)

This project demonstrates an AI-driven automation workflow built using **n8n**, designed to manage and track a monthly budget using natural language input.

## Overview
Expenses or credits are provided through chat input.  
An AI agent interprets the message, determines whether it is a **credit or debit**, applies business logic, and updates the running total automatically.

## How the Workflow Works
1. User enters an expense or credit via chat (e.g., "Paid 50,000 as rent")
2. AI Agent reads and interprets the input
3. The system decides whether it is a credit or debit
4. The total amount is calculated
5. Data is appended to Google Sheets
6. An email alert is triggered when the balance reaches a defined threshold

## QA Perspective
This workflow was designed and validated using a QA mindset:
- Clear business rules
- Validation of AI output
- Handling different input patterns
- Ensuring end-to-end workflow consistency

## Tools Used
- n8n
- OpenAI (AI Agent)
- Google Sheets
- Gmail

## How to Use
1. Import the JSON workflow into n8n
2. Configure credentials for OpenAI, Google Sheets, and Gmail
3. Trigger the workflow using chat input

## Notes
This project focuses on automation logic and quality validation rather than UI or frontend development.

