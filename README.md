# 💰 Zoho Cliq Expense Manager Extension

> **Submission for the Zoho Cliq Trix Competition**

A powerful Zoho Cliq extension designed to streamline the expense reporting and approval process. This tool bridges the gap between **Zoho Cliq** and **Zoho Expense**, allowing employees and managers to handle financial workflows without leaving their chat window.

## 🚀 Key Features

This extension simplifies expense management using two core slash commands:

### 1. `/postexpense` (For Employees)
Allows users to submit expenses directly through Cliq.
* **Workflow:** The user executes the command, fills in the details, and the data is instantly pushed to **Zoho Expense**.
* **Automation:** Once posted, the **Zia Auditor Bot** automatically notifies the assigned approver, ensuring no report goes unnoticed.

### 2. `/summary` (For Approvers/Managers)
Gives managers a quick snapshot of pending and submitted reports.
* **Workflow:** The approver executes the command to receive an aggregated summary of all reports submitted to them, facilitating quicker decision-making.

## 🛠️ How It Works

1.  **User Input:** The user triggers the extension using slash commands in Zoho Cliq.
2.  **Processing:** The extension parses the input and authenticates with the Zoho Expense API.
3.  **Data Sync:** The expense is created or the summary is fetched from the Zoho Expense ledger.
4.  **Bot Notification:** For new expenses, the Zia Auditor Bot is triggered to send a notification card to the respective manager.
eploy the extension.

## 🏆 Context
This project was developed as a solution for the **Zoho Cliq Trix** competition, aimed at extending the capabilities of the Zoho Cliq platform to solve real-world business problems.

---
*Created by [Sanjjey Arumugam and Vigneshwarran S]*
