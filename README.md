# Evaluating Language Models for Harmful Prompt Detection

## Overview

This project aims to evaluate different language models for their ability to detect harmful prompts. The goal is to assess how well these models can identify and mitigate potentially dangerous, unethical, or otherwise harmful inputs before generating a response.

## Setup
```python
!pip install langchain_google_genai
!pip install langchain
!pip install langchain_community
!pip install langchain_anthropic
```

## Evaluation Metrics

The evaluation focuses on the following key metrics:

- **Accuracy**: How often the model correctly identifies harmful and non-harmful prompts.
- **Precision & Recall**: Measurement of the model's ability to correctly classify harmful prompts while minimizing false positives and false negatives.
- **F1 Score**: A balanced metric that considers both precision and recall.
