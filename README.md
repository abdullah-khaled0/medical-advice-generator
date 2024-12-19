# Medical Advice Generator with AI and Web Scraping

This project automates the generation of meaningful medical advice using AI and web scraping. It extracts content from specified websites, processes it through a language model, and outputs structured medical advice in CSV format.

---

## Features

- **Web Scraping**: Extracts medical content from articles on a given website.
- **AI-Powered Analysis**: Uses Google Generative AI to process and generate structured data.
- **CSV Export**: Outputs data in a structured format: `q_type`, `question`, and `answer`.
- **State Management**: Tracks visited links to avoid duplicate processing.
- **Custom Prompting**: Tailored AI prompts to focus on generating relevant medical advice.

---

## Installation

### Prerequisites
- Python 3.8 or later
- Required Python libraries:
  - `langchain`
  - `langchain_google_genai`
  - `FAISS`
  - `BeautifulSoup4`
  - `pydantic`
  - `requests`

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/abdullah-khaled0/medical-advice-generator.git
   cd medical-advice-generator
   ```

2. Install:
   ```bash
   pip install -r requirements.txt
   ```
