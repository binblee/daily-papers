# Daily Papers - Smolagnets Tool Demo

An demo for fetching, downloading, and summarizing the top AI research papers from Hugging Face daily papers. Original code from [https://www.datacamp.com/tutorial/smolagents](https://www.datacamp.com/tutorial/smolagents)

## Overview

This project automatically:
1. Fetches the most upvoted paper from Hugging Face daily papers
2. Downloads the paper from arXiv
3. Reads and summarizes the content using an AI agent

The implementation uses `smolagents` framework with custom tools to create an autonomous agent that performs these tasks end-to-end.

## Installation

```bash
# Clone the repository
git clone <repository-url>
cd daily-papers
uv sync
```

## Running the Agent

Agent code in notebook `main.ipynb`.

## Configuration

To use with DashScope models, set the following environment variables:

```bash
DASHSCOPE_API_BASE=https://dashscope.aliyuncs.com/compatible-mode/v1
DASHSCOPE_API_KEY=<your_api_key>
```
