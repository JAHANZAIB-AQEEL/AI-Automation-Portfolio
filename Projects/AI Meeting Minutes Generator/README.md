# 📝 AI Meeting Minutes Generator

## 📖 Overview

The AI Meeting Minutes Generator is an intelligent automation workflow built with **n8n** and **OpenAI**.

It automatically processes meeting transcripts or notes, extracts key discussion points, summarizes important decisions, identifies action items, assigns responsibilities, stores meeting records, and emails professionally formatted meeting minutes to participants.

---

## 🚀 Features

- AI Meeting Summarization
- Action Item Extraction
- Decision Identification
- Task Assignment
- Google Sheets Integration
- Google Drive Document Generation
- Automated Email Distribution
- End-to-End Meeting Documentation

---

## ⚙️ Workflow

```text
Meeting Transcript
        │
        ▼
Webhook
        │
        ▼
OpenAI Meeting Analysis
        │
        ▼
Extract:
• Summary
• Key Decisions
• Action Items
• Assigned Owners
• Deadlines
        │
        ▼
Store Meeting Record
(Google Sheets)
        │
        ▼
Generate Meeting Minutes
(Google Drive)
        │
        ▼
Send Minutes via Email
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

- Eliminates manual note-taking
- Produces consistent meeting documentation
- Tracks action items automatically
- Improves team accountability
- Stores meeting history centrally
- Saves time after every meeting

---

## 📂 Project Structure

```
AI-Meeting-Minutes-Generator
│
├── README.md
├── workflow.json
└── screenshots
    ├── workflow-overview.png
    ├── ai-summary.png
    ├── google-sheets.png
    ├── meeting-minutes.png
    ├── email-report.png
```

---

## 📷 Screenshots

- Workflow Overview
- AI Meeting Analysis
- Google Sheets Database
- Generated Meeting Minutes
- Email Notification

---

## 🏢 Business Use Cases

- Corporate Meetings
- Client Meetings
- Project Stand-ups
- Board Meetings
- HR Meetings
- Team Collaboration

---

## 👨‍💻 Author

**Jahanzaib Aqeel**

BS Cyber Security Student  
AI Automation Portfolio

---

## 📄 License

MIT License