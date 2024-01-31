# Advanced HR Assistant using Large Language Models

## Overview

The Advanced HR Assistant is a web application developed in Python using Streamlit, Google's Large Language Models, and LangChain to enhance the hiring process. This application aims to provide an intelligent HR assistant capable of assisting in various HR tasks, such as improving job descriptions, shortlisting candidates based on their resumes, conducting chat interviews, and sending notifications and login credentials to shortlisted candidates.

## Functionalities / Features

1. **Job Description Enhancement:**
   - Evaluate job descriptions on a scale of 1 to 10 based on clarity, relevance, attractiveness, and inclusiveness.
   - Provide recommendations to improve job descriptions.
   - Generate suggestions for HR professionals to enhance job posts.

2. **Candidate Resume Scoring:**
   - Upload and analyze candidate resumes in PDF format.
   - Create a matching score (0 to 100) for each candidate based on their alignment with the job description and job post.
   - Generate a summary of the resume along with the reason for the score.
   - Shortlist candidates based on their scores.

3. **Chat Interview:**
   - Conduct chat interviews with shortlisted candidates.
   - Ask essential, preferred, and bonus questions based on the job role and description.
   - Include a CV-specific question tailored to each candidate.
   - Record and store candidate responses for evaluation.

4. **Evaluation of Candidate Responses:**
   - Evaluate candidate responses on a scale of 0 to 100.
   - Consider factors such as accuracy, alignment with the job description, genuineness according to the CV, and non-AI-generated content.
   - Provide a brief explanation for the score for each response.

5. **Automated Email Notifications:**
   - Send automated emails to shortlisted candidates, notifying them of their selection for the chat interview.
   - Include login credentials for the chat round.

## Technologies Used

### Programming Languages

- Python

### Frameworks and Libraries

- Streamlit
- Google's Large Language Models (Palm)
- LangChain
- Pandas, NumPy

### External Tools

- HuggingFaceHub for embeddings
- GmailToolkit for email automation
- PyPDFLoader for reading PDF resumes
- Streamlit for web application development

