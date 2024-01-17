# ATS-system
# ATS Resume Expert

## Overview

This Streamlit application serves as an ATS (Applicant Tracking System) to evaluate resumes against job descriptions. It utilizes the Google Gemini API for content generation and PDF processing.

## Getting Started

1. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
GOOGLE_API_KEY=your_google_api_key

streamlit run your_app_name.py

Usage
Job Description Input:

Enter the job description in the provided text area.
Resume Upload:

Upload a resume in PDF format using the "Upload your resume(pdf)..." button.
Actions:

Click "Tell Me about the resume" to get a professional evaluation.
Click "Percentage Match" to get the percentage match with the job description.
Notes
Ensure that Poppler is installed for PDF processing.
Provide your Google Gemini API key in the .env file.
Troubleshooting
If encountering issues, make sure Poppler is properly installed and the API key is correct.
Dependencies
streamlit
PIL (Pillow)
pdf2image
google.generativeai
