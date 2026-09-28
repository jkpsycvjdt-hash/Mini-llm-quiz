# Mini LLM Benchmark

This project is a small comparison of two Qwen2.5 language models on the 7-item Cognitive Reflection Test (CRT-7). The two models were selected because they differ in  size and capacity. This makes them suitable for a simple comparison of performance.

## Models
- Qwen2.5-0.5B-Instruct
- Qwen2.5-1.5B-Instruct

## Method
The CRT-7 items are stored in a CSV file and passed to both models using the Hugging Face Transformers library.

Each model is asked to provide a final answer in a standardized format (at least, that was the plan). The responses are then compared with the correct answers.

## Purpose
I created this project as a small practical introduction to LLM benchmarking, Python, and Hugging Face.
