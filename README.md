# CrewAI Job Application Assistant

A multi-agent AI system using CrewAI to automate and optimize job application processes for AI/ML roles. This project demonstrates how autonomous agents can collaborate to analyze job postings, profile candidates, tailor resumes, and prepare interview materials.

## Features

- Multi-agent setup with specialized roles: Researcher, Profiler, Resume Strategist, Interview Preparer  
- Uses OpenAI GPT-3.5-turbo for natural language understanding and generation  
- Integrates Serper API for enhanced job market search and scraping  
- Reads candidate resumes and GitHub profiles for personalized content  
- Generates tailored resumes and interview question sets based on job requirements  

## Tech Stack

- Python 3.10+  
- CrewAI  
- OpenAI GPT API  
- Serper API  
- dotenv for environment variables  

## Setup

1. Clone the repo  
```bash
git clone https://github.com/justthzz/crewai-job-application-assistant.git
cd crewai-job-application-assistant
```

2. Install dependencies  
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the root folder with your API keys:  
```ini
OPENAI_API_KEY=your_openai_api_key_here
SERPER_API_KEY=your_serper_api_key_here
OPENAI_MODEL_NAME=gpt-3.5-turbo
```

4. Run the application (in Jupyter Notebook)
```bash
jupyter notebook main.ipynb
```

## Project Structure
```bash
crewai-job-application-assistant/
├── main.ipynb    # Jupyter Notebook entry point for running the multi-agent system
├── utils.py           # Helper functions for API keys and env variables
├── .env               # Environment variables (not committed to GitHub)
├── fake_resume.md     # Sample candidate resume
├── README.md          # This file
├── requirements.txt   # Python dependencies
```

## About

**Thanuja Liyanage**  
Trainee AI/ML Engineer  
University of Westminster  
GitHub: [justthzz](https://github.com/justthzz)

Feel free to contribute or open issues for improvements!
