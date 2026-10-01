# AI Gmail Summarizer + Auto Draft Reply
### 100% Free AI Automation Workflow

## 🔗 Live Demo + Code
**GitHub Repo**: https://github.com/fauzia-annisa/ai-gmail-summarizer-n8n  
**Workflow File**: [Download gmail-ai-workflow.json](./gmail-ai-workflow.json)

## What it does
This workflow automatically checks Gmail every 5 minutes, uses AI to summarize incoming emails, drafts a polite reply, and saves everything to Google Sheets.

Perfect for freelancers, agencies, and small teams to manage inbox 10x faster.

## Tech Stack - $0 Cost
- **n8n Cloud Free** - Workflow automation & scheduling
- **Google Gemini API via n8n Gateway** - AI Summary + Draft Reply
- **Gmail API** - Read new emails + Mark as read
- **Google Sheets** - Auto logging and tracking

## How it Works
1.  **New Email Trigger**: Checks Gmail every 5 minutes for unread emails
2.  **AI Processing**: Gemini creates 3-bullet summary + 2-sentence draft reply
3.  **Save to Sheets**: Logs Date, Sender, Subject, AI Summary, AI Draft
4.  **Mark as Read**: Prevents duplicate processing

## Demo Proof
![n8n Workflow](screenshot-n8n.png)
![Google Sheets Result](screenshot-sheets.png)

**Sample Output:**
| Date | Sender | Subject | AI Summary | AI Draft |
| --- | --- | --- | --- | --- |
| 2026-10-01 | Jane Doe <jane@acme.com> | Project timeline update | - Client requests new timeline  - Needs proposal by Friday | Thanks for the update. I will prepare the proposal and send it by Friday. |

## Setup Guide - 3 Minutes
1.  **Download** `gmail-ai-workflow.json` from this repo
2.  **Import** to n8n Cloud Free: Workflows > Import from File
3.  **Connect** your Gmail and Google Sheets accounts
4.  **Create** Google Sheet with headers: `Date | Sender | Subject | AI Summary | AI Draft`
5.  **Click** `Publish`. Done.

## Cost
**$0 / month**
Uses n8n free tier + n8n Gemini Gateway credits. No OpenAI API key needed.

---
Built for Upwork job: "AI Automation Specialist for a Small AI Workflow"  
Created by @fauzia-annisa
