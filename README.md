[![LinkedIn](https://img.shields.io/badge/LinkedIn-devmuniz-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/devmuniz)
[![GitHub Profile](https://img.shields.io/badge/GitHub-devMuniz02-181717?logo=github&logoColor=white)](https://github.com/devMuniz02)
[![Portfolio](https://img.shields.io/badge/Portfolio-devmuniz02.github.io-0F172A?logo=googlechrome&logoColor=white)](https://devmuniz02.github.io/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-manu02-FFD21E?logoColor=black)](https://huggingface.co/manu02)

# Fine-Tuning DistilBERT for Sentiment Classification on IMDB using LoRA

This repository contains a Jupyter notebook demonstrating how to fine-tune a DistilBERT model for binary sentiment classification on the IMDB dataset using Low-Rank Adaptation (LoRA) for efficient fine-tuning.

The notebook covers: - Loading and preprocessing the IMDB dataset - Setting up DistilBERT model and tokenizer - Configuring LoRA for parameter-efficient training - Training the model - Evaluating performance before and after training - Optional: Saving and loading the fine-tuned model

## Overview

Fine-tuning DistilBERT for sentiment classification on the IMDB dataset using Low-Rank Adaptation (LoRA) for parameter-efficient training. This repository includes a complete Jupyter notebook with step-by-step implementation, from data preprocessing to model evaluation and deployment on Hugging Face Hub.

## Repository Structure

| Path | Description |
| --- | --- |
| `assets/` | Images, figures, or other supporting media used by the project. |
| `.gitignore` | Top-level file included in the repository. |
| `fine_tune_distilbert_imdb_lora.ipynb` | Notebook used for experiments, analysis, or interactive demos. |
| `LICENSE` | Repository license information. |
| `README.md` | Primary project documentation. |
| `requirements.txt` | Python dependency specification for local setup. |

## Getting Started

1. Clone the repository.

   ```bash
   git clone https://github.com/devMuniz02/fine-tune-distilbert-imdb-lora.git
   cd fine-tune-distilbert-imdb-lora
   ```

2. Prepare the local environment.

Install Python dependencies:
```bash
pip install -r requirements.txt
```

3. Run or inspect the project entry point.

Open the notebook files in Jupyter or VS Code to reproduce the workflow documented in the repository.

## Installation

1. Clone this repository: `git clone https://github.com/devMuniz02/fine-tune-distilbert-imdb-lora.git`
2. Install dependencies: `pip install -r requirements.txt`

## Usage

Open the `fine_tune_distilbert_imdb_lora.ipynb` notebook and run the cells in order. The notebook is self-contained and includes all necessary code.

## Results

After training, the model achieves improved accuracy on sentiment classification compared to the untrained baseline.

## License

MIT

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

## References

- Original blog post: [Fine-Tuning Large Language Models](https://medium.com/towards-data-science/fine-tuning-large-language-models-llms-23473d763b91)
- Hugging Face Transformers
- PEFT library for LoRA
