🚀 Job Hunt Automation System (n8n + SerpAPI + Airtable + Telegram)

Finding relevant internships daily is painful — so I automated the entire process.
This workflow fetches jobs, scores them intelligently, stores the best ones, and delivers top matches directly to Telegram every morning.

🎯 Overview

This system scans job listings across the web, ranks them using a custom scoring logic, and sends the top opportunities straight to your phone.
Zero manual searching. Zero wasted time. 100% automated productivity.

⚙️ Tech Stack

n8n — Automation engine

Google Sheets — User profile & job preferences

SerpAPI — Aggregated job search via Google Jobs

Custom JavaScript — Scoring logic (skills, keywords, location, recency, job type)

Airtable — Job database & tracking dashboard

Telegram Bot — Daily job digest notifications

🧠 How the Automation Works

Every day at 9 AM, the workflow runs automatically:

Reads profile data from Google Sheets

Searches Google Jobs via SerpAPI

Parses and structures job results

Scores each job using a weighted system:

Skill Match (40%)

Location Match (25%)

Job Type Match (15%)

Recency (10%)

Keyword Relevance (10%)

Filters high-match roles (≥ 60% score)

Saves all results to Airtable for tracking

Sends top 5 jobs to Telegram with:

Company

Job Title

Match Score

Apply Link

🧩 Features
✔ Smart Job Scoring

Evaluates roles using a weighted algorithm to identify the most relevant matches.

✔ Daily Auto-Execution

Runs at 9 AM without manual intervention.

✔ Airtable Integration

Stores job listings with breakdown scores for analytics.

✔ Telegram Alerts

Instant daily digest of the 5 best opportunities.

✔ Custom Config via Google Sheets

Update your preferences without editing the workflow.

📊 Output Examples
Airtable Dashboard

Job title

Company

Location

Match score

Skill match

Recency

Keyword relevance

Apply link

Posted date

Telegram Digest Sample
🏢 Company: XYZ
💼 Job: Data Science Intern
🔗 Apply: https://...
-----------------
🏢 Company: ABC
💼 Job: Machine Learning Intern
🔗 Apply: https://...

🛠 Workflow Architecture
[Daily Trigger]
      ↓
[Google Sheets: User Profile]
      ↓
[SerpAPI: Job Search]
      ↓
[Parse Job Results]
      ↓
[Score Jobs (JS Logic)]
      ↓
[Filter High Matches]
      ↓
[Prepare Notifications (Email/Slack/Telegram)]
      ↓
[Airtable Storage]
      ↓
[Telegram Bot Notification]

🧩 Key Files

Job Hunt Automation - Optimized.json
Complete n8n workflow


Job Hunt Automation - Optimized

📚 Skills Demonstrated

API integration (SerpAPI, Telegram, Airtable)

Automation with n8n

Data parsing & transformation

Ranking algorithms

No-code + low-code workflow engineering

Notification system design

Real-world productivity automation

🚀 Future Improvements

Resume-based skill extraction

Multi-platform job scraping (LinkedIn, Indeed)

ML model for relevance ranking

Email digest with richer UI

💡 Summary

This system removes the daily grind of job searching by automating the entire pipeline — from discovery to ranking to notification. A real-world productivity boost using smart automation and APIs.
