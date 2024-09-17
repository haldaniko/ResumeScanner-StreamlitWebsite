# ATS Resume Scanner

This is a Streamlit web application for an Applicant Tracking System (ATS) Resume Scanner. It allows users to upload a PDF resume and a job description, and then provides various analyses based on the uploaded documents.

## Features

- **Upload PDF Resume**: Users can upload their resume in PDF format.
- **Input Job Description**: Users can input the job description in a text area.
- **Tell Me About the Resume**: Provides an evaluation of the candidate's profile against the job description, highlighting strengths and weaknesses.
- **Get Keywords**: Identifies specific skills and keywords necessary for the resume to have maximum impact, provided in JSON format.
- **Percentage Match**: Evaluates the percentage match of the resume with the job description, along with keywords missing and final thoughts.

## Installation

```
git clone https://github.com/your_username/ResumeScunner-StreamlitWebsite.git
cd ResumeScunner-StreamlitWebsite

# on macOS
python3 -m venv venv
source venv/bin/activate

# on Windows
python -m venv venv
venv\Scripts\activate

pip install -r requirements.txt

(create your .env file like .env.sample)

streamlit run app.py
```
Application will be available at http://localhost:8501

## Usage
Open the Streamlit app in your browser.
Input the job description in the text area provided.
Upload the PDF resume using the "Upload your resume(PDF)..." button.
Click on the desired action buttons to perform various analyses.