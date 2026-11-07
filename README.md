# Nepal IMF Analysis Using LLMs

## Project Overview
This project analyses Nepal's IMF Country Report No. 25/285 (2025) using Large Language Models (LLMs). It extracts financial indicators, summarises economic information, identifies risks and generates a financial dashboard.

## Models Used
**Three models were used:**

1. **Qwen2.5-7B-Instruct:** Primary LLM for summarisation, financial extraction and RAG answers.
2. **Mistral-7B-Instruct-v0.3:** Evaluator LLM for checking accuracy, completeness and consistency.
3. **all-MiniLM-L6-v2:** Embedding model for FAISS-based document retrieval.

## Technologies
Python, Google Colab (NVIDIA A100 GPU), Hugging Face Transformers, PyMuPDF, FAISS, Pandas and Matplotlib.

## How to Run
1. Open the notebook in Google Colab.
2. Select an A100 GPU.
3. Upload the Nepal IMF PDF.
4. Run all cells sequentially.

**No API keys required.**

## Results
- 9 section summaries
- 6 financial indicator fields
- 7 financial themes
- 4 RAG questions
- 19 LLM evaluations
- 4-panel financial dashboard
- Final validation: 16/16 PASS

## Dataset
IMF Country Report No. 25/285 — Nepal (2025).
