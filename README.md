# AI Engineering Labs

Hands-on AI engineering projects covering model implementation, fine-tuning, structured output, tool use, agent systems, memory, retrieval, evaluation, and observability.

## Overview

This repository documents my practical learning journey from model development to reliable LLM and agent systems.

Each project focuses on understanding not only how an AI technique works, but also how to build, validate, evaluate, and reproduce it in practice.

The repository currently covers:

- Model architecture implementation
- Model fine-tuning and parameter-efficient fine-tuning
- LLM response parsing and validation
- Validation-guided retry pipelines
- Tool and function calling
- Future work on MCP, agent systems, memory, retrieval, and evaluation

## Projects

### Modeling

| Project | Description | Notebook |
|---|---|---|
| RNN with Attention for Machine Translation | Implements an encoder-decoder RNN with an attention mechanism for machine translation. | [Open in Colab](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/ai-engineering-labs/blob/main/modeling/rnn-attention-translation/rnn_attention_translation.ipynb) |
| BERT Emotion Classification | Fine-tunes BERT on the EmpatheticDialogues dataset for emotion classification. | [Open in Colab](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/ai-engineering-labs/blob/main/modeling/bert-emotion-classification/bert_emotion_classification.ipynb) |
| GPT-2 Text Summarization | Fine-tunes GPT-2 to generate summaries from article text. | [Open in Colab](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/ai-engineering-labs/blob/main/modeling/gpt2-summarization/gpt2_summarization.ipynb) |
| Whisper LoRA Fine-tuning | Applies parameter-efficient fine-tuning to Whisper using LoRA. | [Open in Colab](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/ai-engineering-labs/blob/main/modeling/whisper-lora/whisper_lora.ipynb) |

### Structured Output & Tool Use

| Project | Description | Notebook |
|---|---|---|
| Response Parsing | Prompts an LLM to generate JSON, extracts structured content from the model response, and handles parsing errors. | [Open in Colab](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/ai-engineering-labs/blob/main/structured-output-tool-use/response-parsing/response_parsing.ipynb) |
| Response Validation and Retry | Builds a reliable structured-data extraction pipeline with Gemma 4 E2B, Pydantic validation, validation-error feedback, and automatic retries. | [Open in Colab](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/ai-engineering-labs/blob/main/structured-output-tool-use/response-validation-retry/response_validation_retry.ipynb) |
| Gemma Tool Calling | Implements tool schemas, function dispatching, weather lookup, web search, and tool-result feedback using Gemma 4. | [Open in Colab](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/ai-engineering-labs/blob/main/structured-output-tool-use/gemma-tool-calling/gemma_tool_calling.ipynb) |
