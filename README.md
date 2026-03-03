# GPT-from-scratch
This repository is an educational project to learn how large language models (LLMs) work by building one from scratch. A small GPT‑like model is implemented in PyTorch, covering data preparation, tokenizer training, model design, pretraining, fine-tuning and evaluation. The goal is to understand the end‑to‑end process rather than deliver a production system.

## Resources
### Book
Raschka, Sebastian. Build A Large Language Model (From Scratch). Manning, 2024. ISBN: 978-1633437166.
### Used Dataset
For the training of the model, the publicly available Leipzig Corpora Collection (LCC) German Wikipedia sentence dataset is used.

- File: deu_wikipedia_2021_1M-sentences.txt
- Source: Leipzig Corpora Collection (University of Leipzig)
- Domain: German Wikipedia (1,000,000 sentences)
- URL: https://wortschatz.uni-leipzig.de/en/download/deu 

## Getting started
1. Install CUDA 13.0 (optional)
2. Install Python (3.14.3)
2. Install required Python packages ([requirements.txt](requirements.txt))

## Plan

#### 1. Tokenization
OpenAI's _tiktoken_ tokenizer is used to tokenize the beforementioned dataset.

#### 2. Data loader
PyTorchs Dataset and DataLoader is utilized to create a dataloader for generating batched inputs and targets.
