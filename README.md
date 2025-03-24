# AI Resume Screening & Candidate Ranking System

This is an AI-powered resume screening and ranking system built using Streamlit and Python. The application extracts text from uploaded resumes, compares them against a given job description using TF-IDF and cosine similarity, and ranks candidates based on relevance.

## Features
- Upload multiple resumes in PDF format.
- Enter a job description to compare resumes.
- AI-powered ranking of resumes based on relevance.
- Provides suggestions for resume improvements.

## Technologies Used
- Streamlit
- PyPDF2
- scikit-learn
- Pandas
- NumPy

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Swethamrecw/Resume_ranking
   cd resume-screening
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```

## Usage
1. Upload PDF resumes.
2. Enter a job description.
3. View the ranked resumes and improvement suggestions.



