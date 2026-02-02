# Fine-Tuning DistilBERT for Sentiment Classification on IMDB using LoRA

This repository contains a Jupyter notebook demonstrating how to fine-tune a DistilBERT model for binary sentiment classification on the IMDB dataset using Low-Rank Adaptation (LoRA) for efficient fine-tuning.

## Overview

The notebook covers:
- Loading and preprocessing the IMDB dataset
- Setting up DistilBERT model and tokenizer
- Configuring LoRA for parameter-efficient training
- Training the model
- Evaluating performance before and after training
- Optional: Saving and loading the fine-tuned model

## Model

The fine-tuned model is available on Hugging Face Hub: [manu02/distilbert-base-uncased-lora-text-classification](https://huggingface.co/manu02/distilbert-base-uncased-lora-text-classification)

## Requirements

- Python 3.8+
- See `requirements.txt` for dependencies

## Installation

1. Clone this repository: `git clone https://github.com/devMuniz02/fine-tune-distilbert-imdb-lora.git`
2. Install dependencies: `pip install -r requirements.txt`

## Usage

Open the `fine_tune_distilbert_imdb_lora.ipynb` notebook and run the cells in order. The notebook is self-contained and includes all necessary code.

## Results

After training, the model achieves improved accuracy on sentiment classification compared to the untrained baseline.

## References

- Original blog post: [Fine-Tuning Large Language Models](https://medium.com/towards-data-science/fine-tuning-large-language-models-llms-23473d763b91)
- Hugging Face Transformers
- PEFT library for LoRA

## License

MIT