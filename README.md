# Wikipedia QA System

## Overview
This project is a Question-Answering (QA) System built using the Wikipedia API. It combines BM25 ranking for retrieval with a Sentence Transformer for semantic similarity refinement.

## Features
- Fetches content from Wikipedia using the API.
- Preprocesses text for cleaner analysis.
- Uses BM25 and a pre-trained Sentence Transformer to rank and retrieve relevant answers.

## Installation
Install the required dependencies using:
```bash
pip install wikipedia-api nltk gensim rank-bm25 sentence-transformers transformers evaluate
