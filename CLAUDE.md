# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Research project exploring AI search pipeline efficiency, built around the CRAG (Comprehensive RAG Benchmark) dataset. The project is in early/exploratory stage, primarily using Jupyter notebooks for data analysis.

## Data

- **`crag_task_1_and_2_dev_v4.jsonl`**: Main dataset (~2706 records). Each record contains:
  - `query`, `answer`, `alt_ans` — question-answer pairs
  - `search_results` — retrieved web search results
  - `domain`, `question_type`, `static_or_dynamic` — metadata categorization
  - `query_time`, `interaction_id`, `split` — identifiers and timing

## Development

- **Language**: Python 3 with Jupyter notebooks
- **Notebook**: `data.ipynb` — primary notebook for data exploration and analysis
- Run notebooks with `jupyter notebook` or VS Code's notebook interface
