\# AI Career Agent



\## Overview

This project is an AI-powered career assessment agent built using n8n and LLM APIs. It takes a job description and a candidate's resume (PDF), evaluates skill gaps, and generates a personalized learning plan.



\---



\## Features

\- Extracts skills from job description and resume

\- Generates interview questions

\- Simulates answers

\- Evaluates candidate proficiency

\- Provides learning plan with time estimates



\---



\## Tech Stack

\- n8n (workflow automation)

\- Groq API (LLM)

\- HTML (UI)



\---



**## Local Setup Instructions**


1. Install n8n

npm install -g n8n

n8n

You should be able to see:
Editor is now available at:
http://localhost:5678


2. Open browser:

http://localhost:5678



3.Import Workflow

Click “New Workflow”
Top right → ⋮ (three dots)
Click Import from file
Select: AI_resume_assessor.json



4. Add API Key

Open HTTP Request node

Add Groq API key= **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**



5. Run

Click "Listen for Test Event"

Open index.html

Upload PDFs





