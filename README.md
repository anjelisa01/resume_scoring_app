# Resume Scoring App (ON GOING)

This repository contains a local application that evaluates resumes against job descriptions using natural language processing and large language models (LLMs). The system accepts user input in the form of a resume (PDF) and a job description (TXT), processes and analyzes the content, and returns section-wise semantic scores along with insights generated by the LLM.

## Overview

The application workflow:
1. Accepts a PDF file (resume) and a plain text file (job description) as input.
2. Extracts and cleans text from both files.
3. Normalizes and preprocesses the text data.
4. Performs semantic similarity scoring between each resume section and the job description.
5. Sends the processed content to an LLM for deeper analysis and contextual evaluation.
6. Presents the results via a local Streamlit interface.

## Components

- **Backend API**: Handles file input, preprocessing, semantic analysis, and LLM communication.
- **Model Layer**: Performs text normalization, embedding-based scoring, and LLM integration.
- **Frontend (Streamlit)**: Provides a simple web interface for uploading files and viewing results.
- **Dockerized Deployment**: All services are containerized and configured for local deployment using Docker and Docker Compose.
