# Recruitment-Process-Automation

An automated hiring pipeline built in **n8n** that screens job applicants with AI, routes them by fit, and notifies the hiring team — no manual review needed for the first pass.

## How it works

**Form submission → AI screening → Smart routing → Notify & Log**

1. Candidate submits a Google Form.
2. **Gemini AI** scores their skills/experience against the role and returns a **Shortlist / Review / Reject** verdict.
3. Shortlisted and Review candidates trigger an instant **email alert** to the hiring team.
4. Every candidate is logged to a **Candidate Tracker** sheet with score, tag, and AI reasoning.

## Stack

`n8n` · `Google Gemini API` · `Google Sheets` · `Gmail`

## Why it matters

Turns hours of manual resume screening into a fully automated, consistent, AI-scored pipeline — from application to shortlist in minutes.

## Setup

1. Import the workflow JSON into n8n.
2. Connect Google Sheets + Gmail credentials.
3. Add your Gemini API key.
4. Point it at your Form Responses sheet and a Candidate Tracker sheet.
5. Activate — done.
