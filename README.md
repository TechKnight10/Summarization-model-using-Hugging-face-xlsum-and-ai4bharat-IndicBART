
# Summarization Model Using Hugging Face XLSum and AI4Bharat IndicBART

This repository contains the code and resources for training a summarization model using the Hugging Face XLSum dataset in conjunction with the AI4Bharat IndicBART model. The project is implemented in Google Colab with a T4 cloud GPU for efficient processing.

## Dataset

The model is trained on the [XLSum dataset](https://huggingface.co/datasets/csebuetnlp/xlsum), which provides a diverse collection of news articles in multiple languages. This dataset allows the model to learn effective summarization strategies across various languages and topics.

## Model Architecture

The AI4Bharat IndicBART model is used as the core architecture for this summarization task. IndicBART is a transformer-based model optimized for Indic languages, making it suitable for summarizing content in a wide range of languages from the Indian subcontinent.

## Implementation

- **Platform**: The code is implemented in Google Colab.
- **GPU**: Model training and evaluation are accelerated with a T4 cloud GPU.
- **Frameworks**: Uses the Hugging Face Transformers and Datasets libraries to facilitate the loading, fine-tuning, and inference of the model.

## Usage

1. Clone this repository.
2. Open the `summarization_model.ipynb` notebook in Google Colab.
3. Run the cells to load the dataset, fine-tune the model, and generate summaries.

## Dependencies

- `transformers`
- `datasets`
- `torch`

Install the dependencies using:
```bash
pip install transformers datasets torch
