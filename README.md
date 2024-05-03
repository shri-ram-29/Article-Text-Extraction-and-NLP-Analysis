# Article Text Extraction and NLP Analysis

This repository contains a Python-based system for extracting article text from URLs, performing natural language processing (NLP) analysis, and computing various text analysis metrics.

## Project Overview

The main objectives of this project are:

- Extract article title and text from a list of provided URLs.
- Perform text analysis on the extracted articles.
- Compute NLP variables such as sentiment scores, readability indices, and lexical features.
- Generate an output file with the computed NLP variables and input data.

## Repository Contents

- `input.xlsx`: An Excel file containing the list of URLs for article text extraction.
- `code.ipynb`: The actual code.

## Dependencies

The required Python dependencies are listed in the `requirements.txt` file. The primary libraries used in this project include:

- BeautifulSoup (for web scraping)
- pandas (for data manipulation)
- nltk (for natural language processing)
- textstat (for readability calculations)
