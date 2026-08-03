# AI-Spam-Email-Classification-Agent

An AI-powered spam detection workflow built using **n8n** and **OpenAI**.

The workflow automatically receives incoming form submissions, filters invalid entries, classifies whether a message is spam or genuine using an LLM, and stores the result in separate Google Sheets.

Built as part of the **Outskill Generative AI Accelerator Bootcamp (14 Days)**.

---

# Problem

Businesses receive dozens or even hundreds of contact form submissions every week.

Many of these include:

- Promotional emails
- Scam messages
- Bot-generated content
- Irrelevant enquiries

Manually reviewing every submission wastes valuable time.

This workflow automates that process.

---

# Solution

The workflow automatically:

✅ Receives a form submission

↓

✅ Removes empty messages

↓

✅ Uses an AI model to determine whether the enquiry is spam

↓

✅ Routes the message

- Spam → Spam Sheet
- Genuine → Genuine Enquiries Sheet

No manual review is required.

---

# Workflow

Form Submission

↓

Filter Empty Messages

↓

OpenAI Spam Classification

↓

If Spam?

├── Yes → Google Sheet (Spam)

└── No → Google Sheet (Genuine)

---

# Tech Stack

- n8n Cloud
- OpenAI
- Google Sheets
- Conditional Routing
- AI Classification

---

# Features

- AI-powered spam detection
- Automatic routing
- No-code workflow
- Google Sheets integration
- Modular workflow
- Easy to extend

---

# Why I Built This

I wanted to understand how Large Language Models can automate repetitive business workflows.

Instead of using traditional keyword-based spam filters, I explored using an AI model capable of understanding the intent behind messages.

This project demonstrates how AI can be integrated into real-world business automation with minimal manual intervention.

---

# Future Improvements

- Confidence score
- Email notifications
- CRM integration
- Slack alerts
- Spam analytics dashboard
- Multi-language support

---

# Screenshots

(Add screenshots here)

- Workflow
- Google Sheet
- AI Node
- IF Node

---

# Learning Outcomes

Through this project I learned:

- Building workflows in n8n
- Prompt engineering for classification
- AI automation design
- Conditional workflow logic
- Google Sheets integration
- Business process automation

---

# Author

Sneha Chaurasia
Computer Science Engineering (AI & ML)
AI Automation | Agentic AI | LLM Workflows
