# NLP Course Project

A Natural Language Processing course project developed by **Mathias Nygaard Larsen and Andreas Melbye** at the University of Copenhagen.

## Overview

This repository contains our work from the NLP course, where we explored different approaches to language processing and question answering.

We experimented with baseline methods, neural networks and transformer-based models, including DistilBERT and RoBERTa.

The project involved data preprocessing, model training, evaluation and comparing different experimental setups.

## Technologies

- Python
- PyTorch
- Hugging Face Transformers
- Jupyter Notebook / Google Colab

## Repository structure

- `NLP.ipynb` – Combined notebook containing work from multiple weeks
- `experiments/` – Individual weekly experiments and model variations
- `best_model.pt` – Saved model weights
- `test.json` – Test data
- `requirements.txt` – Project dependencies

## Running the experiments

The notebooks were developed primarily using Google Colab with GPU access.

Some experiments require the `translated_data` directory, which should be uploaded to Google Drive at:

`/content/drive/MyDrive/translated_data/`

Install dependencies using:

```bash
pip install -r requirements.txt
```

The notebooks in `experiments/` document the different approaches explored throughout the course. Some may require additional dependencies or adjustments to run in a new environment.

## Authors

- Mathias Nygaard Larsen
- Andreas Melbye