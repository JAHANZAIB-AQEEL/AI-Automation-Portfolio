# 🎫 AI Customer Support Ticket Classifier

## 📖 Overview

The AI Customer Support Ticket Classifier is an intelligent customer service automation workflow built with **n8n** and **OpenAI**.

It automatically receives customer support requests, analyzes the ticket content using AI, classifies the issue type, determines priority, recommends the appropriate support department, stores ticket information, and sends automated acknowledgment emails.

---

## 🚀 Features

- AI Ticket Classification
- Issue Category Detection
- Priority Assignment
- Department Routing
- AI Ticket Summary
- Google Sheets Integration
- Google Drive Ticket Reports
- Automated Customer Email Notifications

---

## ⚙️ Workflow

```text
Customer Support Ticket
          │
          ▼
Webhook
          │
          ▼
OpenAI Ticket Analysis
          │
          ▼
Determine:
• Ticket Category
• Priority Level
• Assigned Department
• AI Summary
          │
          ▼
Store Ticket
(Google Sheets)
          │
          ▼
Generate Ticket Report
(Google Drive)
          │
          ▼
Send Customer Acknowledgment
```

---

## 🛠 Technologies Used

- n8n
- OpenAI GPT-5
- Google Sheets
- Google Drive
- Gmail / SMTP
- Webhooks

---

## 💼 Business Benefits

- Automates ticket classification
- Reduces manual support workload
- Routes tickets to the correct department
- Improves response times
- Maintains a centralized support database
- Generates AI-powered ticket summaries

---

## 📂 Project Structure

```
AI-Customer-Support-Ticket-Classifier
│
├── README.md
├── workflow.json
└── screenshots
    ├── workflow-overview.png
    ├── ticket-analysis.png
    ├── google-sheets.png
    ├── ticket-report.png
    ├── customer-email.png
```

---

## 📷 Screenshots

- Workflow Overview
- AI Ticket Classification
- Google Sheets Database
- Ticket Report
- Customer Acknowledgment Email

---

## 🏢 Business Use Cases

- Customer Support Centers
- IT Help Desks
- SaaS Companies
- Technical Support Teams
- E-commerce Customer Service
- Managed Service Providers
- Enterprise Service Desks

---

## 👨‍💻 Author

**Jahanzaib Aqeel**

BS Cyber Security Student  
AI Automation Portfolio

---

## 📄 License

MIT License