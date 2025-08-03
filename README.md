# Jobmateai
Job mate ai helps freshers and job seekers find 🤖 matching job openings based on their 🫴🏻resume
# 🤖 Resume Bot Automation – n8n + Telegram

This project automates the process of collecting resumes via Telegram and sending notifications.

## 🚀 How It Works
- ✅ Telegram Bot triggers when a resume (PDF) is uploaded
- 📥 Extracts the file and sends it to job filter HTTP service
- 📤 Sends job match results back via Telegram

## 🛠️ Tools Used
- [n8n](https://n8n.io/) – Workflow Automation
- Telegram Bot API
- HTTP Request node
- PDF Extractor

## 📁 Files
- `resume_job_bot.json` – n8n workflow export

## 🔒 Note
This is a personal automation project made for fresher job seekers.

## 🧠 Workflow
1. User sends `/start` to the Telegram bot.
2. Bot asks for user the to upload resume.
3. n8n takes the input → sends it to Open AI for analysis.
4. Open ai compares it with job descriptions in a job portals with help of api.
5. The most relevant job is returned and sent back via Telegram.

## 📬 Contact
Created by Jithin – [Behance](https://www.behance.net/gallery/231239499/Job-Mate-AI-Smart-Resume-to-Job-Matching-Automation)
