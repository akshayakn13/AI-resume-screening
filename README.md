# AI Resume Screening Workflow

An automated resume screening system built using n8n and OpenAI that analyzes uploaded resumes, extracts key candidate information, scores applicants, stores results in Google Sheets, and sends professional screening reports via email.

## Features

- Resume PDF upload through n8n Form
- Automatic text extraction from resumes
- AI-powered candidate analysis using OpenAI
- Candidate scoring and skill extraction
- Recommended role generation
- Structured JSON output
- Google Sheets database integration
- Automated email reports to candidates

## Tech Stack

- n8n
- OpenAI GPT
- Google Sheets API
- Gmail API
- PDF Text Extraction

## Workflow

Resume Upload → PDF Extraction → AI Analysis → JSON Parsing → Google Sheets → Email Report

## Screenshots

### n8n Workflow

![Workflow](screenshots/workflow.png)

### Google Sheets Database

![Google Sheets](screenshots/sheets.png)

### Email Report

![Email Report](screenshots/email-report.png)

## Use Cases

- HR Recruitment Automation
- Candidate Screening
- Talent Acquisition
- Resume Ranking
- Applicant Tracking

## Future Enhancements

- PDF Report Generation
- ATS Integration
- Multi-Candidate Ranking Dashboard
- Recruiter Analytics Dashboard
- Candidate Shortlisting Automation
