# 📘 ITAI2376 Capstone Project: AI Research Assistant Agent


## Project Description
This AI Research Assistant Agent helps users quickly research any topic by searching the web, extracting article content, and generating concise summaries. It combines web scraping, natural language processing, and search APIs to provide organized and easy-to-understand information, saving users time and effort.

## Features
- Searches the web using DuckDuckGo for relevant articles on a given topic  
- Scrapes article content from the top search results  
- Summarizes article texts using Hugging Face Transformers (`distilbart-cnn-12-6` model)  
- Generates basic APA-style citations for sources  
- Validates user input to block unsafe queries  
- Logs user feedback for potential improvements  

## Technologies Used
- Python 3  
- [duckduckgo_search](https://pypi.org/project/duckduckgo-search/) for free web search  
- [requests](https://docs.python-requests.org/en/latest/) for HTTP requests  
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) for HTML parsing  
- [transformers](https://huggingface.co/docs/transformers/index) by Hugging Face for summarization  
- Google Colab (development environment)  

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-research-assistant.git
   cd ai-research-assistant

