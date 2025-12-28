# AI-Powered-Lead-Engagement-Email-Automation-System
ArtFigure is an AI-driven automation workflow designed for product-based and service agencies. It automatically processes incoming leads, generates personalized sales emails using contextual project examples, and applies human-in-the-loop approval before sending emails to potential clients.

This system ensures accuracy, personalization, and quality control in outbound communication.

🧠 Core Features

AI-generated personalized sales emails

Context-aware project matching using a project database

Human-in-the-loop approval & revision system

Gmail integration for real email delivery

Google Sheets used as CRM and knowledge base

Modular AI agents for generation, review, and revision

🏗️ System Workflow Overview

🔁 Workflow Logic

Form Submission

User submits:

Full Name

Company Name

Email

Intent

Budget

Timeline

CRM Storage

Lead is appended to Google Sheets

AI Sales Agent

Generates a customized email

Uses:

Lead details

Project intent

Relevant past project examples

Email Formatting

JSON parser structures:

Subject

Greeting

Body (paragraph-based)

Closing

Human-in-the-Loop Approval

Email is reviewed

Approved → sent to lead

Rejected → sent to revision agent

Revision Loop

Feedback is applied

Email regenerated

Loop continues until approval

🧩 Agency Service Domains Supported

ArtFigure supports automated outreach for agencies working in:

✅ Lead Generation

✅ Content Creation

✅ Onboarding Automation

✅ General Tech Solutions

Each domain has pre-stored project results used by the AI for persuasive email writing.

📊 Example Project Database (Used by AI)

Stored in Google Sheets and used as contextual memory:

Lead Generation (Real Estate, Marketing Agencies)

Content Creation (Brand Growth Campaigns)

Onboarding Automation (SaaS & Service Companies)

General Tech (Custom Dashboards & Systems)

These examples allow the AI to dynamically match lead intent with relevant past success stories.

🛠️ Tech Stack

n8n – Workflow automation

Google Sheets – CRM & knowledge base

Gmail API – Email delivery

LLM (Chat Model) – Email generation & revision

JSON Output Parsers – Structured email formatting

Human Approval Node – Quality control

📂 Repository Contents
Folder	Purpose
/workflows	n8n workflow JSON
/prompts	AI system & agent prompts
/parsers	Email & lead JSON parsers
/docs	Project explanations & samples
/screenshots	Visual workflow evidence
🎯 Use Cases

AI sales automation

Agency lead nurturing

CRM-driven email personalization

Human-approved AI communication

SaaS & service onboarding workflows

👩‍💻 Author

Tanzeela Sharif
Data Science & AI Automation Enthusiast
Skilled in AI agents, workflow automation, data analytics, and intelligent systems.

⭐ Future Enhancements

Multi-language email support

Lead scoring automation

Follow-up email sequences

WhatsApp / SMS integration

Analytics dashboard
