# News Article Ingestion & NLP Pipeline

## Overview

This project implements an end-to-end data pipeline that ingests live news articles from RSS feeds, scrapes full article content, cleans and structures unstructured text, and prepares the data for downstream NLP and large language model (LLM) workflows.

The notebook demonstrates real-world data engineering challenges including external data ingestion, HTML parsing, text cleaning, structured dataset creation, and API-driven AI processing.

---

## Pipeline Architecture

1. Parse RSS feed (BBC News) to retrieve article metadata  
2. Extract article URLs  
3. Scrape full article HTML content using BeautifulSoup  
4. Clean and structure raw text data  
5. Store articles in structured JSON-ready format  
6. Integrate OpenAI API for downstream text processing  

---

## Technologies Used

- Python
- Requests
- Feedparser
- BeautifulSoup
- JSON
- OpenAI API
- Jupyter Notebook

---

## Skills Demonstrated

- External data ingestion
- Web scraping and HTML parsing
- Unstructured text preprocessing
- Data pipeline design
- API integration
- NLP-ready dataset preparation

---

## File Structure

- `gptpipelineclean.ipynb` — Complete ingestion and processing pipeline

---

## Notes

- API keys are handled using environment variables and are not included in this repository.
- This pipeline can be extended to support summarization, classification, topic modeling, or trend analysis.

