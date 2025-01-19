# Financial AI Analyst

## Overview
This project is an advanced AI-powered financial analysis tool that leverages multiple AI models and web search capabilities to provide comprehensive financial insights.

## Features
- Web search integration for real-time financial information
- AI-powered financial analysis using Groq and OpenAI models
- YFinance integration for stock market data
- DuckDuckGo search capabilities

## Prerequisites
- Python 3.8+
- API keys for OpenAI and Groq (optional)

## Installation
1. Clone the repository
```bash
git clone git@github.com:LohiyaH/financial-intelligence-agent.git
cd financial-ai-analyst
```

2. Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Set up environment variables
Create a `.env` file in the project root and add:
```
OPENAI_API_KEY=your_openai_api_key
GROQ_API_KEY=your_groq_api_key
```

## Usage
Run the main script:
```bash
python financial_agent.py
```

## Dependencies
- phidata
- python-dotenv
- yfinance
- duckduckgo-search
- fastapi
- uvicorn
- groq
- openai

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## Disclaimer
This tool is for informational purposes only and should not be considered financial advice.
