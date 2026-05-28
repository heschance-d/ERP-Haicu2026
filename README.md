# ERP-Haicu2026

This repository contains the prototype code used in our study on interface transparency in RAG-based cultural heritage search.
The prototype compares two interface conditions:
- **System A:** low-transparency RAG interface with direct synthesised answers.
- **System B:** high-transparency RAG interface with in-text citations, archival evidence, provenance cues, and source-based perspectives.

## How to run in Google Colab
1. Open `ERP_RAG.ipynb`.
2. Add the following secrets in Colab:
   - `GOOGLE_API_KEY`
   - `FILE_SEARCH_STORE_NAME`
3. Run all cells.

## How to run locally

```bash
pip install -r requirements.txt
export GOOGLE_API_KEY="your-api-key"
export FILE_SEARCH_STORE_NAME="your-file-search-store-name"
python app.py
