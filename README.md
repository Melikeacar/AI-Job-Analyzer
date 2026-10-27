# AI Job Analyzer

AI Job Analyzer is a Python-based project that uses the Gemini API to analyze job postings and generate structured reports.

The project was developed to practice web scraping, prompt engineering, JSON processing, and LLM API integration.

## Features

- Extracts job posting content from a given URL.
- Cleans HTML content using BeautifulSoup.
- Analyzes job descriptions with Google Gemini.
- Extracts job titles, company names, technical skills, experience requirements, and responsibilities.
- Generates a structured JSON analysis.
- Creates a Turkish job analysis report in Markdown format.

## Technologies

- Python
- Google Gemini API
- Requests
- BeautifulSoup
- JSON
- Jupyter Notebook

## How It Works

1. The user provides a job posting URL.
2. Python retrieves the webpage content.
3. BeautifulSoup extracts and cleans the text.
4. Gemini analyzes the job posting and returns JSON data.
5. A second Gemini API call generates a Turkish Markdown report.

## Installation

Clone the repository and install dependencies:

```bash
pip install -r requirements.txt
```

Create a `.env` file in the project directory:

```env
GEMINI_API_KEY=your_api_key_here
```

Open `main.ipynb` in Jupyter Notebook or VS Code and run the cells in order.

## Notes

This is an educational project developed to explore LLM integration and prompt engineering. Some websites may restrict automated content extraction.