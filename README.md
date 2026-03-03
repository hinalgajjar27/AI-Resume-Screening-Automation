# AI Resume Screening Automation Project

## Project Overview

This project is an AI-powered Resume Screening Automation system developed using n8n, Google Gemini API, Google Drive, Google Sheets, and Gmail.

The system automatically evaluates resumes based on a predefined job description, assigns a relevance score, and performs automated shortlisting or rejection with email communication.

The goal of this project is to reduce manual effort in the hiring process and demonstrate real-world workflow automation using AI.

---

## How the System Works

1. The HR team uploads a resume (PDF format) into a specific folder in Google Drive.
2. The n8n workflow is triggered automatically when a new file is added.
3. The system extracts text from the uploaded PDF.
4. The extracted resume text is sent to the Google Gemini API for analysis.
5. The AI extracts the candidate’s name and email and assigns a score out of 100 based on how well the resume matches the job description.
6. A conditional check is performed:
   - If the score is greater than 75, the candidate is shortlisted.
   - If the score is 75 or below, the candidate is rejected.
7. The candidate’s details (Name, Email, Score, Status) are stored in Google Sheets.
8. An automated email is sent to the candidate with the evaluation result.
9. The resume file is moved to either the “Shortlisted Candidates” folder or the “Rejected Candidates” folder.

---

## Technologies Used

- n8n (Workflow Automation Platform)
- Google Gemini API (AI Resume Evaluation & Scoring)
- Google Drive API (Resume Storage & File Management)
- Google Sheets API (Candidate Data Storage)
- Gmail API (Automated Email Communication)
- PDF Resume Text Extraction
- Conditional Workflow Logic
---

## Key Features

- AI-based resume scoring
- Automated shortlisting and rejection
- Structured data extraction (Name, Email, Score)
- Conditional workflow logic
- Google Sheets integration for record keeping
- Automated professional email communication
- Organized file management in Google Drive
- End-to-end automation of the resume screening process

---

## Google Drive Folder Structure

AI Resume Screening  
- Resume uploads  
- Shortlisted Candidates  
- Rejected Candidates  

---

## Workflow Logic Summary

Resume Upload  
→ Extract Text  
→ Send to Gemini API  
→ Parse AI Response  
→ Conditional Check (Score > 75)  
→ Store Data in Google Sheets  
→ Move Resume File  
→ Send Email Notification  

---

## Project Significance

This project demonstrates:

- Practical API integration  
- AI prompt engineering  
- Workflow automation using n8n  
- Conditional logic implementation  
- Real-world hiring automation use case  
- Backend process automation skills  

It reflects the ability to combine artificial intelligence with business process automation to solve real operational problems.
