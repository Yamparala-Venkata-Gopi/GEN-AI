# ATS Resume Expert

## Overview

ATS Resume Expert is a Streamlit application designed to help job seekers optimize their resumes by comparing them against job descriptions using advanced AI models. This app uses Google Generative AI (Gemini Pro Vision) to evaluate the content and provide feedback on how well the resume aligns with the job requirements.

## Features

- **PDF to Image Conversion:** Converts the first page of the uploaded resume PDF into an image for processing.
- **Resume Evaluation:** Provides professional feedback on how well the resume matches the job description.
- **ATS Match Percentage:** Calculates the percentage match of the resume with the job description, highlighting missing keywords and offering final thoughts.

## Requirements

- Python 3.8+
- Streamlit
- dotenv
- pdf2image
- PIL (Python Imaging Library)
- google-generativeai

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Venkata-Gopi-Personal-Projects/ATS-Resume-Expert.git
   cd ATS-Resume-Expert
2. **Install the required Python packages:**
   ```bash
   pip install -r requirements.txt
   
3. **Run the Streamlit app:
 ```bash
  streamlit run your_script_name.py