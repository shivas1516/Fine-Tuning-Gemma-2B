# Fine-Tuned Gemma Model using LoRA

This repository contains the code and model for fine-tuning the **Gemma** language model using **LoRA** (Low-Rank Adaptation) in Keras. This approach allows efficient fine-tuning of large-scale models by reducing the number of trainable parameters while retaining the original model's effectiveness.

## Project Overview

This project aims to fine-tune the **Gemma** model using LoRA, adapting it for specific NLP tasks while maintaining efficiency. The fine-tuning process was conducted in Keras, with a focus on limiting memory usage by capping the input sequence length to 256 tokens.

### Key Features:
- **Base Model**: [Gemma](https://huggingface.co/gemma)
- **Fine-tuning Technique**: LoRA (Low-Rank Adaptation)
- **Framework**: Keras 
- **Sequence Length**: 256 tokens
- **Training Epochs**: 1
- **Batch Size**: 1

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/shivas1516/Fine-Tuning-Gemma-2B.git
   ```
## Install Dependencies

2. You can install all dependencies using:
   ```bash
   pip install -r requirements.txt
   ```
## Fine-Tuned Data
   ```bash
   !wget -O databricks-dolly-15k.jsonl https://huggingface.co/datasets/databricks/databricks-dolly-15k/resolve/main/databricks-dolly-15k.jsonl
   ```
## Performance

This model is expected to perform well on tasks such as text classification, text generation, and other sequence-related NLP tasks. However, you may further fine-tune it for your specific use case.

## How to Fine-Tune Further

If you want to fine-tune this model further on your dataset, you can do so by loading the model and running additional training steps.
