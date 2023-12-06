# Named Entity Recognition

## Description

Two fine-tuned BERT model using the MultiNERD Named Entity Recognition dataset
The models are also available at:
[https://huggingface.co/emilyblah/distilbert-base-uncased-finetuned-ner](https://huggingface.co/emilyblah/distilbert-base-uncased-finetuned-ner)
[https://huggingface.co/emilyblah/distilbert-base-uncased-finetuned-5tagOnly-ner](https://huggingface.co/emilyblah/distilbert-base-uncased-finetuned-ner)

## Files and Directories

- `model_finetuning.ipynb`: Notebook for fine-tuning models.
- `evaluation.ipynb`: Notebook for model evaluation.
- `requirements.txt`: List of required dependencies.

## Usage

1. Install dependencies:
   ```bash
   pip install -r requirements.txt

2. To reproduce the Fine-tuning of the Models (referred to as systemA and systemB in the script):

    Open model_finetuning.ipynb in a Jupyter notebook environment.
    Follow the instructions in the notebook to fine-tune models.

3. To evaluate the fine-tuned Models:

    Open evaluation.ipynb in a Jupyter notebook environment.
    Run the notebook cells sequentially to evaluate the models.

## Requirements

See `requirements.txt`