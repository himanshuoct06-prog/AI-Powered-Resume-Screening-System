# AI-Powered Resume Screening & Interview Scheduling System

## Overview

This project automates the recruitment process using AI-powered resume screening and interview scheduling.

The solution uses Google Gemini, n8n Cloud, Google Sheets, Gmail, Calendly, and Google Meet to evaluate resumes, calculate candidate scores, classify applicants, and send automated notifications.

## Features

* Resume Upload Form
* AI Resume Evaluation
* Candidate Scoring System
* Automated Candidate Classification
* Google Sheets Integration
* Interview Invitation Email
* Rejection Notification Email
* Calendly Scheduling Integration
* Google Meet Integration

## Technology Stack

* n8n Cloud
* Google Gemini AI
* Google Sheets
* Gmail
* Calendly
* Google Meet

## Workflow

1. Candidate uploads resume.
2. Resume text is extracted.
3. AI Evaluation Agent analyzes candidate profile.
4. Scoring Agent calculates candidate score.
5. Candidate is classified as:

   * Strong Match (≥90)
   * Shortlisted (60-89)
   * Rejected (<60)
6. Candidate evaluation details are stored in Google Sheets.
7. Automated emails are sent.
8. Shortlisted candidates receive interview scheduling links.

## Repository Structure

```text
README.md
User_Guide.pdf
job_description.pdf
resume_screening_workflow.json
screenshots/
```

## Future Enhancements

* ATS Integration
* Candidate Ranking Dashboard
* AI Interview Question Generator
* Power BI Analytics Dashboard

## Author
Name : Himanshu Srivastava
Email : himanshu.oct06@gmail.com