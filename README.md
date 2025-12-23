# 🤖 AI-Powered Resume Analyzer & CSV Generator using LangChain

## Project Overview
Recruiters and HR teams often receive bulk resumes in compressed ZIP files containing PDF and DOCX formats. Manually reviewing and extracting key details from each resume is time-consuming, repetitive, and error-prone. This project automates resume understanding and structured data extraction using LangChain, Prompt Templates, and Structured Output Parsers, and outputs the results as a CSV file through a Streamlit web application.

## Key Features
- Upload a ZIP file containing multiple resumes  
- Supports PDF and DOCX resume formats  
- Uses LLMs with LangChain for intelligent resume parsing  
- Extracts structured information using a fixed schema  
- Automatically generates a CSV file  
- Allows direct CSV download from the Streamlit UI  

## Problem Statement
HR teams commonly face several challenges such as inefficient manual resume screening, highly varied resume layouts and formats, inconsistent extraction of skills, links, and summaries, and the absence of structured data for effective filtering and analytics.

## Solution Approach
This project implements an LLM-powered resume processing pipeline that accepts a ZIP folder containing multiple resumes, extracts text from each resume file, converts unstructured resume text into structured data using LangChain, enforces a consistent output schema using a TypedDict Output Parser, aggregates all resume data into a single CSV file, and enables CSV download through a Streamlit web interface.

## Architecture Workflow
ZIP Upload → Resume Extraction → Text Parsing → LLM Processing (LangChain) → Structured Output → CSV Generation → Download

## Extracted Fields (Example Schema)
- Full Name  
- Email Address  
- Phone Number  
- Skills  
- Education  
- Experience Summary  
- GitHub / LinkedIn / Portfolio Links  

## Tech Stack
- Python  
- LangChain  
- OpenAI / LLM APIs  
- Streamlit  
- PDF & DOCX Parsers  
- Pandas (CSV generation)  

## Installation
Clone the repository using  
`git clone https://github.com/your-username/ai-resume-analyzer-langchain.git`  

Navigate to the project folder using  
`cd ai-resume-analyzer-langchain`  

Install dependencies using  
`pip install -r requirements.txt`  

## Run the Application
Run the Streamlit app using  
`streamlit run app.py`  

## Use Cases
This system can be used for automated resume screening for HR teams, skill-based candidate filtering, resume data analytics, and talent pool management.

## Future Enhancements
Planned enhancements include resume ranking based on job descriptions, skill matching and scoring, database integration using SQL or NoSQL systems, and multi-language resume support.

## Contributing
Contributions are welcome. Fork the repository and submit a pull request to contribute.

## Acknowledgements
LangChain, OpenAI, and the Streamlit Community.

**Automate resume screening with AI — faster, smarter, and structured.**
